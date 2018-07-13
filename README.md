# Report Receiving System Portal
Banko Sentral ng Pilipinas 
Information Technology Sub-Sector

(BRD ITSS-092217-22)


Development of Credit Surety Fund
(Database Management System)

This Project is Develop in Java EE 8 + Oracle Database 12c + Apache Tomcat 8 + AngularJS + Spring 

* used updated DATE & Time API features of JEE8 and usable in JPA / JSF
---------------------------------------------------------------------

public class DateConverter

implements AttributeConverter<Instant, Date> {

public Date ConvertToDatebaseColumn(Instant instant) {
    return Date.from(instant);
    }
    
public Instant ConvertToEntityAttribute(Date date){
        return date.toInstant();
        }
}

---------------------------------------------------------------------
        
* Embed XBRL Core API for Report Receiving System - Report Maintenance Module


