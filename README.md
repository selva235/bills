# bills basic crud operation

**command to run** : mvn spring-boot:run

POST: http://localhost:8084/bills
**Json Body:**
{
	"billNumber" : 123,
	"billedTo" : "selva",
	"billedDate" : "26-11-21",
	"billedPrice" : 20,
	"taxOnBill" : 10.2,
	"totalPrice" : 20
}
------------------------------------------
To get all the bills:
GET : http://localhost:8084/bills
------------------------------------------
To get specific bills by id :
GET : http://localhost:8084/bills/1
------------------------------------------
To get specific bills by date : 
GET : http://localhost:8084/bills/due/26-11-21
------------------------------------------
