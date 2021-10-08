# 220-Assignment1
This is assignment 1 of Full stack technology

var fs = require('fs');
//create directory
fs.mkdir('practical',function(){

});

//remove directory
fs.rmdir('practical',function(){

});

//write file
fs.writeFile("mytext.txt","This is for write file, This file made by mansi tailor",function(err){
    if(err)
    {
        console.log(err);
    }
    else
    {
        console.log("File Save Successfully..");
    }
});

//read file
fs.readFile("mytext.txt","utf8",function(err,data){
    if(err)
    {
        console.log(err)
    }
    else
    {
        console.log(data);
    }
});

//Delete File

fs.unlink("mytext.txt",function(err){
    if(err)
    {
        console.log(err);
    }
    else
    {
        console.log("File Deleted Successfully..");
    }
});

//Append data to file

fs.appendFile("mytext.txt","This is for appending file data content",function(err){
    if(err)
    {
        console.log(err);
    }
    else
    {
        console.log("File Content Saved..");
    }
});

//Update/Replace file with new data

fs.readFile("mytext.txt", 'utf8', function (err,data) {
    if (err) {
      return console.log(err);
    }
    //It will be replacing the word mansi to a Mansi M Tailor in a text file mytext.txt 
    var newValue = data.replace(/mansi/, 'Mansi M Tailor');
  
    fs.writeFile("mytext.txt", newValue, 'utf8', function (err) {
       if (err)
       {
            return console.log(err);

       }
    });
  });

  //Rename File

  fs.rename('mytext.txt','mytextrename.txt',function(err){
      if(err)
      {
          console.log(err);
      }
      else
      {
          console.log("File name changed/rename..");
      }
  })
