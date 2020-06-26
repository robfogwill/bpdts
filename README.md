# BPDTS Test Task

## Test Steps:
1. Select this [![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/d73a35359282fc8295a9#?env%5Bbpdts%5D=W3sia2V5IjoiY2l0eSIsInZhbHVlIjoiIiwiZW5hYmxlZCI6dHJ1ZX0seyJrZXkiOiJpZCIsInZhbHVlIjoiIiwiZW5hYmxlZCI6dHJ1ZX0seyJrZXkiOiJ1cmwiLCJ2YWx1ZSI6Imh0dHA6Ly9icGR0cy10ZXN0LWFwcC12Mi5oZXJva3VhcHAuY29tIiwiZW5hYmxlZCI6dHJ1ZX1d) button to open the collection in postman.
2. Select the "Get users" test within the collection, select the down arrow next to the "Send" button and select "Send and Download".
3. Save the file and make a note of the location.
4. Select the "Runner" button from the top left.
5. Select the collection and then update the following settings:
- Environemnt: bpdts
- Data: (select the downloaded file from step 3)
 -Data File Type: application/json
- Iterations: 1000
- Delay: 5ms
 -Keep variable values (ticked)
6. Deselect the "Get users" test as this was only required to populate the data file.
7. Select the "Run bpdts Collection" button.
