# BPDTS Test Task

## Test Steps:
1. Select this [![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/d73a35359282fc8295a9#?env%5Bbpdts%5D=W3sia2V5IjoiY2l0eSIsInZhbHVlIjoiIiwiZW5hYmxlZCI6dHJ1ZX0seyJrZXkiOiJpZCIsInZhbHVlIjoiIiwiZW5hYmxlZCI6dHJ1ZX0seyJrZXkiOiJ1cmwiLCJ2YWx1ZSI6Imh0dHA6Ly9icGR0cy10ZXN0LWFwcC12Mi5oZXJva3VhcHAuY29tIiwiZW5hYmxlZCI6dHJ1ZX1d) button to open the collection in postman.
2. Set the environment to "bpdts" from the dropdown in the top right.
3. Select the "Get users" test within the collection, select the down arrow next to the "Send" button and select "Send and Download".
4. Save the file and make a note of the location.
5. Select the "Runner" button from the top left.
6. Select the collection and then update the following settings:
- Environemnt: bpdts
- Data: (select the downloaded file from step 3)
 -Data File Type: application/json
- Iterations: 1000
- Delay: 1 ms
- Keep variable values (ticked)
7. Deselect the "Get users" test as this was only required to populate the data file.
8. Select the "Run bpdts Collection" button.
