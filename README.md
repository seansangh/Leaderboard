# Leaderboard

*Display results*

This is an app that allows you to display, compare, and sort results.


...

**Home Page**

<img src="/Leaderboard.PNG" title="home page" alt="home page" width="500px">


---


## Table of Contents 

> Sections
- [Sample Code](#Sample_Code)
- [Installation](#installation)
- [Features](#features)
- [Contributing](#contributing)
- [Team](#team)
- [FAQ](#faq)
- [Support](#support)
- [License](#license)


---

## Sample Code

```javascript
// code

  var url= "https://raw.githubusercontent.com/freeCodeCamp/ProjectReferenceData/master/cyclist-data.json";
  var input= [];
  
  var ajax1= $.ajax({url:url,
          type: 'GET'
                    }); 
          
       $.when(ajax1).done(  
          function(data){ 
            data=JSON.parse(data); 
            var arr=[];
            
            for(var i=0; i< data.length; i++){
              arr.push(data[i]['Name']);
              arr.push(data[i]['Time']);
              arr.push(data[i]['Year'])
              input.push(arr)
              arr=[];
            }
            
   

class MyC extends React.Component{
   constructor(props){
     super(props);
     this.state={input:[]}
   }
   
   render(){

     return(
      <div>
         
         <div className="wo">
           {input.map((x,i)=>
      <table className="col-xs-12 ga" id={"x"+i}>
      <td className="col-xs-1 d0 d" id={"ad"+i+"0"}>
        {i+1}
      </td>
      <td className="col-xs-3 d1 d" id={"ad"+i+"1"}>
        {x[0]}
      </td>
      <td className="col-xs-4 d2 d" id={"ad"+i+"2"}>
        {x[2]}
      </td>
      <td className="col-xs-4 d3 d" id={"ad"+i+"3"}>
        {x[1]}
      </td>
      </table>
        )}      
           
           
         </div>

      
      </div>
     );
   }
 }

ReactDOM.render(<MyC />, document.getElementById('bM'));
            
            
})

```

---

## Installation


### Setup


>  install npm package

```shell
$ npm install
```

- For all of the packages used, refer to the package.json file [here](/package.json).

---

## Features
## Usage (Optional)
## Documentation (Optional)
## Tests (Optional)
## Contributing
## Team

> Contributors/People

| [**seansangh**](https://github.com/seansangh) |
| :---: |
| [![seansangh](https://avatars0.githubusercontent.com/u/45724640?v=3&s=200)](https://github.com/seansangh)    |
| [`github.com/seansangh`](https://github.com/seansangh) | 

-  GitHub user profile

---

## FAQ

- **Have any *specific* questions?**
    - Use the information provided under *Support* for answers

---

## Support

Reach out to me at one of the following places!

- Twitter at [`@sean13nay`](https://twitter.com/sean13nay?lang=en)
- Github at [`seansangh`](https://github.com/seansangh)

---

## Donations (Optional)

- If you appreciate the code provided herein, feel free to donate to the author via [Paypal](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=4VED5H2K8Z4TU&source=url).

[<img src="https://www.paypalobjects.com/webstatic/en_US/i/buttons/cc-badges-ppppcmcvdam.png" alt="Pay with PayPal, PayPal Credit or any major credit card" />](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=4VED5H2K8Z4TU&source=url)

---

## License

[![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](http://badges.mit-license.org)

- **[MIT license](http://opensource.org/licenses/mit-license.php)**
- Copyright 2019 © <a>S.S.</a>
