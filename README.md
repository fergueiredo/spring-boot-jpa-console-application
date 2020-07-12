# Spring Boot JPA Console Application

Spring framework formation exercise.

This project should:

- [x] Create simple spring boot console application
- [ ] Create the following entities and their relations.
- [ ] Create simple CRUD for both Customer and Order by implementing JpaRepository.  

Create queries that can answer the following questions:

- [ ] All orders done by a specific customer (customer id)
- [ ] The customer with the highest order
- [ ] Query to find the customer with highest amount of total purchases

## Entities

<table>
    <tr>
        <th>Customer</th>
        <th></th>
        <th>Order</th>
    </tr>
    <tr>
        <td>
            name: String<br>
            address: String<br>
            birthday: Date<br>
            /age: Number
        </td>
        <td>
            <pre style="padding: 0px;">1                0..*</pre>
            <hr  style="margin-top: -1em; margin-bottom: 0;">
            <pre style="padding: 0px;">customer         order</pre>
        </td>
        <td>
            date: Date<br>
            number: String<br>
            amount: Number<br>
            /total: Number<br>
        </td>
    <tr>
    <tr>
        <td><br></td>
        <td><br></td>
        <td><br></td>
    <tr>
</table>