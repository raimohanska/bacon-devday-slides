!SLIDE bullets
# frp w/ js #
* juha paananen @raimohanska

!SLIDE code

    managers = new ArrayList<Employee>()
    for (int i = 0; i < employees.size(); i++) {
      Employee e = employees.get(i);
      if (e.title.equals("manager")) {
        managers.add(e);
      }
    }
    return managers;

!SLIDE code

    filter ((== "manager") . title) employees

!SLIDE bullets incremental
#fp - lists
* filter, map, fold, zip, >>=

!SLIDE bullets incremental
#frp - events
* filter, map, scan, merge, combine, >>=

!SLIDE bullets incremental
#bacon.js
* @raimohanska
* open-source

!SLIDE 
#EventStream

!SLIDE
#stream-of-events (really)

!SLIDE
#Property

!SLIDE
#value-as-function-of-time

!SLIDE bullets
* mouseClicks :: EventStream
* mousePos :: Property

!SLIDE center
![regform-ui](images/registration-form-ui.png)

!SLIDE center
![regform-simple](images/registration-form-simple.png)

!SLIDE center
![regform-thorough](images/registration-form-thorough.png)

!SLIDE center
![pacman](images/bacon-of-bacon.jpeg)
