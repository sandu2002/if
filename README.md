void main() {
  
  //program data
  
  String month = "Feb";
  bool isMonthValid = true;
  String season = "";
  
  if(month=="Jan" || month == "Feb" || month == "March"){
    season = "Spring";
  }
  if(month=="JApr" || month == "Jun" || month == "July"){
    season = "Summer";
  }
  if(month=="Aug" || month == "Sep" || month == "Oct"){
    season = "Autumn";
  }
  if(month=="Nov" || month == "Dec"){
    season = "Winter";
  }
  
  print(season);
  
}

