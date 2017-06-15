# ImpactFlow Frontend Code Challenge

You own an online event management platform called FooFlow. Your platform allows people to buy tickets for events all over the world. However, your users have spoken, and they are requesting the ability to add a ticket purchasing (checkout) widget to their own websites. This widget will, of course, be powered by your API.

## Requirements:

Create an embeddable checkout widget that consumes the following JSON string:

```json
{
  "event": {
    "id": 1,
    "name": "Impactflow's 20th Annual Mario Cart Tournament",
    "date": "Wed Aug 2 2017 12:00:00 GMT-0700 (PDT)",
    "tickets": [
      {
        "id": 1,
        "name": "General Admission",
        "price": 50.00,
        "available": 50
      },
      {
        "id": 2,
        "name": "Early Bird",
        "price": 25.00,
        "available": 5
      },
      {
        "id": 3,
        "name": "Participant",
        "price": 99.99,
        "available": 10
      }
    ]
  }
}
```

### Your widget must:

* show the event name and date
* list the available tickets
* allow the user to add 1 or more tickets
* prevent the user from adding more than `available` tickets
* display the total number of added tickets next to each ticket type
* show a "buy" button
* show a summary of their order when the "buy" button is clicked

### Your widget probably should:

* be lightweight and load quickly
* be responsive and accessible
* have appropriate tests to capture core functionality

### Implement 2 additional features that you think would be beneficial.

---

When you are finished, push your solution to a GitHub repo. **Your README should include:**

* an example of how to use your widget and any instructions necessary to consume your widget
* a description of key decisions that you made to come up with your solution
