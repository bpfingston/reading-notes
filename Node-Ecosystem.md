# Node Ecosystem, TDD, CI/CD  
  
## Review, Research, and Discussion  
    1.  Describe (in plain English) what Array.map() does  
        - array.map() iterates over each element within an array, running a provided function over each of those elements, returning an array of the same length.   
    2.  Describe (in plain English) what Array.reduce() does  
        - array.reduce() iterates over each element within an array, running a provided method or callback function over each element, and returning a single value as a result.  
    3.  Provide code snippets showing how to use superagent() to fetch data from a URL and log the result  
        a.  With normal Promise .then() syntax  
            - superagent.get(url)  
                .then( data => {  
                    let forceChar = data.body.results.map( person => {  
                        let personObj = {};  
                        personObj[person.name] = person.url  
                        console.log(personObj)  
                    })  
                })  
                .catch(err => {  
                    console.error(err);  
                })  
        b.  Again with async / await syntax  
            -   var cityData = await superagent.get(`https://geocode.xyz/${cityName}?json=1`);  
  
                let newCity = {  
                    name: cityData.body.standard.city,  
                    lat: cityData.body.latt,  
                    long: cityData.body.longt,  
                }  

                console.log(`${newCity.name}: Lat: ${newCity.lat}, Long: ${newCity.long};`);  
            };  
    4.  Explain promises as though you were mentoring a Code 301 level student  
        - Promises allow you to run code through JS without it interfering with other pieces of code, and accessing the eventual value whenever the process is complete.  
    5.  Are all callback functions considered to be Asynchronous? Why or Why Not?  
        - A callback function can be either Asynchronous or Synchronous, because it depends on when in the timeline a callback is being used that determines it.