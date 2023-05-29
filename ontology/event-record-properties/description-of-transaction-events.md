# Description of Transaction Events

#### **Duration**&#x20;

* Term: otgevents:duration
* Equivalent property: schema:duration
* Data type: Duration or Text
* Description: The length of the lease, rental, or term of enslavement before manumission in sales contract.
* Usage:
* Input: Single

#### **Currency**

* Term: otgevents:currency
* Equivalent property: schema:currency
* Data type: Text&#x20;
* Description: The currency in which the monetary amount is expressed.
* Usage: Input will vary based on time and place. Use a general base term to indicate the currency (dollars, pounds, etc.), even if smaller units of that currency are being used. If a local currency is being used, indicate the location with an annotation or in the Description field (Maryland pounds, British pounds, etc.).&#x20;
* Input: Multiple

#### **Price**

* Term: otgevents:price
* Equivalent property: schema:price
* Data type: Integer or Text
* Description: The numeric representation of the price or evaluation for a transaction.
* Usage: This property offers a way to capture the monetary elements of a transaction. For transactions that also include bartered items, list those elements with Price Component. In the case of pounds, separate the units with periods (e.g. £ 31.05.02).
* Input: Multiple

#### **Price Component**

* Term: otgevents:priceComponent
* Equivalent property: schema:priceComponent
* Data type: Text
* Description: Indication of combined elements in a commercial transaction.
* Usage: If a transaction lists multiple forms of payment or exchange, rather than a total price, list those elements here, (i.e. livestock, trade goods, agricultural products, exchanges of enslaved people).
* Input: Multiple

#### **Good or Service**

* Term: otgevents:typeOfGood
* Equivalent property: schema:typeOfGood
* Data type: Text
* Description: Materials involved in a commercial transaction&#x20;
* Usage:
* Input: Multiple

#### **Task Performed**

* Term: otgevents:taskPerformed
* Equivalent property:
* Data type: Text&#x20;
* Description: The type of work performed.
* Usage:
* Input: Multiple

#### **Contract Terms**

* Term: otgevents:contractTerms
* Equivalent property:
* Data type: Text
* Description: The terms of a sale, legal, or employment contract.
* Usage:
* Input: Multiple

#### **Exchanged For**

* Term: otgevents:exchangedFor
* Equivalent property:
* Data type: Text
* Description: The goods or services exchanged in transaction. Might be used in lieu of monetary payment.&#x20;
* Usage:
* Input: Multiple
