!SLIDE bullets
# frp w/ js #
* juha paananen @raimohanska

!SLIDE center
![tweet](images/tweet.png)

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
* filter, map, fold, zip, flatMap

!SLIDE bullets incremental
#frp - events
* filter, map, scan, merge, combine, flatMap

!SLIDE bullets incremental
#bacon.js

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

!SLIDE center
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
ssh://git@git.reaktor.fi/public/jpaanane/bacon-devday-code

!SLIDE
#wrap it up

!SLIDE
#@raimohanska
