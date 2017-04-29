# event-registration

package event.registration;


//  Below is the tmeplate for the Event object


public class Event {
    
    // Basic fields
    public String name;
    public String location;
    public String date;
    
    // Get and set Event Name
    public String getName() {return name;}
    public void setName(String name) {this.name = name;}
    // Get and set Event Location
    public String getLocation() {return location;}
    public void setLocation(String location) {this.location = location;}
    //Get and set Event Date
    public String getDate() {return date;}
    public void setDate(String date) {this.date = date;}
    
    // Default constructor
    public Event() {
        this.name = "none";
        this.location = "none";
        this.date = "none";
    }
    
    // Construct with pre-defined fields
    public Event(String name, String location, String date) {
        
        this.name = name;
        this.location = location;
        this.date = date;
           
    }
    
    // Print method
    public void printEventInfo() {
       
        System.out.println("Event name: " + name);
        System.out.println("Event location: " + location);
        System.out.println("Event date: " + date);
        
    }
    
}
