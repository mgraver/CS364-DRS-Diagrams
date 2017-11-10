@startuml

title PersonalCalendar


class PersonalCalendar {
  +daysOfMonth : Array<Day>
  +Month: string
  +Year: Int
  +Date: Int
  +PersonalCalendar(string, int, int)
  +getMonth() : String
  +getYear() : Int
  +getDate() : Int
  +setMonth() : void
  +setYear( ): Int
  +setDate() : Int

}

@enduml

