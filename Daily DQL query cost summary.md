The Daily DQL query cost summary Workflow gets the last 24 hours of DQL Query consumption and calculates the total cost based on the bill rate. 
It also gives a list of the top consuming users, and sends this data as a plaintext email to the specified address(es) in the email task.

Pre-Reqs:
1. Replace <BILL RATE> in the total_query_cost task with your customer's DQL query bill rate.
2. In the send_email task, enter the email address(es)  of whoever the report should be sent to each day.
