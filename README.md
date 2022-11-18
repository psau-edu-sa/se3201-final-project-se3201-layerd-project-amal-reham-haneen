# Layered Architecture Pattern For Hungerstation App

<img src= "https://user-images.githubusercontent.com/98769338/201519056-aeeef4d1-4e59-4e10-bfd6-76ec4abc84df.png" width="300" >



## SUITABLE PATTERNS AND WHY?
<img src= "https://user-images.githubusercontent.com/98769338/201519419-026a388e-171e-49d2-85e6-6a2333dc91e2.png" width="300" >


## TRADE-OFFS :
### Flexibility vs. Simplicity
#### Some systems need to have a lot of flexibility and expandability built into them because you know you're starting with the kernel of an idea and it's going to get bigger
### Space vs. Time
#### If time is of the essence then you'll want to start pulling tricks like pre-computing possible values similar to what OLAP cubes do. Ever wonder how you can report on billions of rows across a range of dimensions so quickly? The aggregations are precomputed so that by the time you ask, the data is ready for you (or very close).
### Latency vs. Throughput
#### Which do you need to optimize, the time for the first result or the number of results you can process in a given period of time? Think of this in terms of moving people a quarter mile, do you need a bus to move a lot of people or a motorcycle to get the first person there in the shortest amount of time?


## FUNCTIONAL REOUIREMENTS AND NON-FUNCTIONAL REOUIREMENTS

### FUNCTIONAL REOUIREMENTS
<img src= "https://user-images.githubusercontent.com/118071141/202722708-8b22c7c6-8f4b-4178-8977-c087c2904eb3.png" width="300" >
<div>
<img src= "https://user-images.githubusercontent.com/98769338/201520121-75194379-cd1e-471c-88c5-4f5f5c71a120.png" width="200" >
<img src= "https://user-images.githubusercontent.com/98769338/201520231-e288fe3a-7ea3-4823-a5c4-1d6f21c044d9.png" width="200" >
</div>

### NON-FUNCTIONAL REOUIREMENTS
#### Performance requirements: it determines the acceptable response times for the system functions.
#### Reliability requirements: determining the required factors to get the desired reliability from the software system at the submission time.
#### Maintainability requirements: Hungerstation management system is being developed by the php programming language.

<div>
<img src= "https://user-images.githubusercontent.com/98769338/201520906-ca5d8cb8-b454-4d4f-baa5-0c6e97e2bff0.png"  >
<img src= "https://user-images.githubusercontent.com/98769338/201520972-af2f0cbf-945b-4bf7-b279-9812b051ac65.png"  >
</div>

<img src= "https://user-images.githubusercontent.com/98769338/201520780-887830ba-660c-4f77-8ac4-7f76dd5ea166.png" width="300" >
