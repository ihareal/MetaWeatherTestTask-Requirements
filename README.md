# MetaWeatherTestTask-Requirements
---
__Requirements for meta weather test task.__
The intent of the associated application is to prompt the user to enter a location, and then using that location
query a public API to download the weather info and store it to disk every couple of seconds.
The most immediate issue with the code currently is that the data is not written immediately to file once it has
been downloaded.
A copy of the test project is provided in the attached zip file that comes with this document.
Documentation related to the API utilised in this test can be found here (https://www.metaweather.com/api/)

---
__CODING CHALLENGES__
1. As a starting point you are required to fix the program so that it correctly writes the data as intended.
2. Update the program so that it accepts either a location name, or lat / long co-ordinates and then
consequently uses the correct API URL depending on what is entered:
    * https://www.metaweather.com/api/location/search/?query=london
    * https://www.metaweather.com/api/location/search/?lattlong=50.068,-5.316
3. Refactor and fix the code to improve the overall project. There is a lot of opportunities to show your skill
and knowledge in undertaking these improvements. (This test application has intentionally been written
in a poor manner to provide you with opportunities to show your knowledge and skill in producing clean,
optimised, high quality code).

---
[Refactored solution is here](https://github.com/ihareal/MetaWeatherTestTask)