# jat-oop-interface-segregationAnalyze the code and refactor it (Interface segregation):

public interface RestaurantInterface {
    
     void acceptOnlineOrder();
     void acceptTelephoneOrder();
     void acceptWalkInCustomerOrder();
     void payOnline();
     void payInPerson();

}