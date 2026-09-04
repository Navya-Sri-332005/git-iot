
HR Travels, a
reputable travel agency situated in Delhi, has recognised the need to
streamline the management and monitoring of booking numbers related to various
modes of travel. The agency's manager approaches a software developer to help
in their process. You, being the software developer, develop a Java program
based on the requirements.

Functional Requirements

    
        
            Req.#
            Requirement Description
             Type (Class Name)Method Name 
            Parameters 
            Description 
        
    
    
        
            1.
            Add the booking number and its travel mode to the map.
             TicketBooking addTicketBookingDetails
            String bookingNumber, String travelMode
            This method should add the bookingNumber and travelMode into the booking map, which is implemented as a hash map.Note: bookingMap takes  bookingNumber as key and travelMode as value.Constraints:bookingNumber is case-sensitive.
                
                
                
                
            
        
        
            2.
            Filter the booking number based on the travel mode.
                
            
             TicketBooking findBookingNumbersByTravelMode 
            
            String travelMode
            
                
                This method accepts travelMode as the parameter and filter the booking numbers for the specified travel mode.
                Constraints:  
                
                
                    travelMode is case-insensitive.It should return a list of booking numbers.
                
                
                
            
        
    

You are provided with the main method as a code template, and it is excluded from evaluation.

Note:Edit only the TicketBooking class to implement the business requirements.The methods and the constructor should be public, and the attributes of the class should be private.In the Sample Input / Output provided, the highlighted text in bold corresponds to the input given by the user and the rest of the text represents the output.Ensure that the names for classes, attributes, and methods are provided as specified in the question description.Please do not use System.exit(0); to terminate the program.


Sample Input / Output 1:  
Enter the number of bookings to be added
3
Enter the booking details (Booking Number: Travel Mode)
HR2345:Bus
HR7689:Train
HR5647:Flight
Enter the travel mode to find booking numbers
train
Booking numbers based on train are
HR7689
 
Sample Input / Output 2:  
Enter the number of bookings to be added
3
Enter the booking details (Booking Number: Travel Mode)
HR5346:Bus
HR8435:Train
HR2346:Bus

Enter the travel mode to find booking numbers
flight
No bookings were found for flight
