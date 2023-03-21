$(document).ready(function () {
  console.log("Name Game Startup");

  $("#btnGetFacts").click(function () {
    $("#coolNameFactsOutput").html();

    let userName = $("#userName").val();
    console.log("user name = ", userName);

    console.log("spirit animal f/n = ", getSpiritAnimal(userName));

    console.log("button clicked");

 $("#coolNameFactsOutput").html(getSpiritAnimal(userName) + (vowel_count(userName)));

  });
});


// Determine spirit animal
function getSpiritAnimal(name) {

  if (name.length == 3) {
  return "You are a snake - mysterious! ";
} else if (name.length > 10) {
  return "You are a butterfly - graceful! ";
} else if (name.length == 4) {
  return "You are a cuttlefish - intriguing! ";
} else if (name.length == 5) {
  return "You are an elephant - gentle giant! ";
} else if (name.length == 6) {
  return "You are a raven - intelligent! ";
} else if (name.length == 7) {
  return "You are a mouse - resoureceful! ";
} else {
  return "You are a kangaroo - athletic! ";}
}

// Count name vowels
function vowel_count(name)
{
  var vowel_list = 'aeiouAEIOU';
  var vcount = 0;
  
  for(var x = 0; x < name.length ; x++)
  {
    if (vowel_list.indexOf(name[x]) !== -1)
    {
      vcount += 1;
    }
  
  }
  return "Your name has " + vcount +  " vowels!";
}
