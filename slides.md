!SLIDE bullets
# FRP / bacon.js #
* juha.paananen@reaktor.fi

!SLIDE code

    List<Employee> managers = new ArrayList()
    for (Employee employee : employees) {
      if (employee.title.equals("manager")) {
        managers.add(e);
      }
    }
    return managers;

!SLIDE code

    employees.filter(_.title == "manager")

!SLIDE bullets incremental
#fp - lists
* filter, map, fold, zip 

!SLIDE bullets incremental
#frp - events
* filter, map, scan, merge, combine

!SLIDE bullets incremental
#bacon.js

!SLIDE center
![tweet](images/tweet.png)

!SLIDE center
#EventStream

!SLIDE center
![eventstream](images/eventstream.jpg)

!SLIDE center
#Property

!SLIDE center
![property](images/property.jpg)

!SLIDE bullets
* mouseClicks :: EventStream
* mouseButtonState :: Property

!SLIDE center
#API

!SLIDE center
![wrong](images/wrong.png)

!SLIDE center
![fail](images/huge-uml.jpeg)

!SLIDE center
![observable](images/observable-hierarchy-simple.png)

!SLIDE center transition=fade
![observable](images/observable-hierarchy.png)

!SLIDE center
![regform-ui](images/registration-form-ui.png)

!SLIDE center
![regform-simple](images/registration-form-simple.png)

!SLIDE center
![regform-thorough](images/registration-form-thorough.png)

!SLIDE center
![regform-thorough](images/baconized.png)

!SLIDE center
![regform-bacon](images/registration-form-bacon.png)

!SLIDE center
![bacon](images/bacon-of-bacon.jpeg)

!SLIDE
#let's get started

!SLIDE
#ready? get the code!

!SLIDE
https://github.com/raimohanska/bacon-devday-code

!SLIDE
#wrap it up

!SLIDE
juha.paananen@reaktor.fi
#@raimohanska
