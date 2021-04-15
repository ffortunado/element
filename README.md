# element

@startuml test
class Dummy {
  String data
  void methods()
}

class Flight {
   flightNumber : Integer
   departureTime : Date
}
class Flight2 {
   flightNumber : Integer
   departureTime : Date
}
Dummy -|> Flight
Dummy -|> Flight2
@enduml
