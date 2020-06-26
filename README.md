# BPDTS Test Task

## Test Steps:
1. Select this [![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/9d1a4ac3b6435600dd14#?env%5Bbpdts%5D=W3sia2V5IjoiY2l0eSIsInZhbHVlIjoiIiwiZW5hYmxlZCI6dHJ1ZX0seyJrZXkiOiJpZCIsInZhbHVlIjoiIiwiZW5hYmxlZCI6dHJ1ZX0seyJrZXkiOiJ1cmwiLCJ2YWx1ZSI6Imh0dHA6Ly9icGR0cy10ZXN0LWFwcC12Mi5oZXJva3VhcHAuY29tIiwiZW5hYmxlZCI6dHJ1ZX1d) button to open the collection in postman.
2.
3. Select the "Runner" button from the top left.
4. Select the collection and then update the following settings:
- Environemnt: bpdts
- Iterations: 1000
- Delay: 5ms
- Data: (select the downloaded GetUsersResponse file)
 -Data File Type: application/json
 -Keep variable values (ticked)
5. Deselect the "Get users" test as this was only required to populate the GetUsersResponse file.
6. Select the "Run bpdts Collection" button.
