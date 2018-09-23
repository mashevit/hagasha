# hagasha

no signiture in teller: -  public int createAccount(String owner, int balance) {

after the end of project signiture was probably: - public int createAccount(Owner owner, int balance) {

with corresponding db changes.
therefore file createaccount.jsp is with error.
createaccountv1.jsp createaccountv2.jsp and everything else should work.


adjustments:
x-a datasource according to video https://www.youtube.com/watch?v=vKAcCzCmkKM
java:/MysqlXADS

jms queue for mdb: according to 


 https://www.kevinhooke.com/2014/10/03/adding-a-jms-queue-to-wildfly-8-x/
 
 should be changed also in mdbtest.jsp
 
 for my own reference : repository path to put in eclipse: mashevit/hagasha(.git)
 
 standalone-xts.xml
