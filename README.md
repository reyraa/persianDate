#PersianDate
>is a free and open source library to convert Georgian date to Persian ( Jalali ) calendar date.

## how to use
Just link the library to your page it's done!

## Methods
**1) getDay()**

returns a number between 0 and 6, representing the day in week. pass 'name' as parameter and it'll return the name of the -day in Persian

**2) getDate()** 

returns a number between 1 and 31, representing the day in month.

**3) getMonth()**

-returns a number between 0 and 11 representing the month in year. pass 'name' as parameter and it'll return the name of the month in Persian

**4) getYear()**

-returns a four digit number as year. also you can pass the string 'short', and get the year in two digits

**5) getFullDate()**

-returns an object containing day , month and year.

**6) toJSON()**

-returns astring in the standard Persian date format: yyyy/mm/dd




 * **v0.1.0** - 2014-06-05
   - First commit.
 * **v0.1.1** - 2014-06-10
   - defining methods similar to Javascript Date object

## Author
**Ali Haghighatkhah**

- [Twitter](https://twitter.com/reyraa)
- [Github](https://github.com/alihaghighatkhah) 


THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED
TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL
THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF
CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS
IN THE SOFTWARE.
