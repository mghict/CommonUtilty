# CommonUtilty
This package includes a series of classes needed in programming

## Installation
Use the package manager [pip](https://pip.pypa.io/en/stable/) to install foobar.

```bash
pip install foobar
```

## Usage
### Converters
This namespace contains a series of classes for conversion

#### NumberToEnglishWord
namespace Mgh.Common.NumberToPersianWord

```bash
string numberToWord=ConvertToEnglish.NumberToWord("1234");
```
```bash
string numberToWord=ConvertToEnglish.NumberToWord("1,234");
```
```bash
string numberToWord=ConvertToEnglish.NumberToWord("1234",ConvertType.American);
```
```bash
string numberToWord=ConvertToEnglish.NumberToWord("1234",ConvertType.British);
```

Default is American





#### NumberToPersianWord
namespace Mgh.Common.NumberToPersianWord
```bash
string numberToWord=ConvertToPersian.NumberToWord("1234");
```


### Extension Methods
#### DateTimeExtensions
```Methods
DateTime sendDate=DateTime.Now;

# DateTime to JalaliDate
string toJalaliDate = sendDate.ToJalaliDate()

# DateTime to JalaliDate with Time
string toJalaliDateTime = sendDate.ToJalaliDateTime()

# DateTime ToJalaliDate with Time and Milisecond
string toJalaliDateTimeMilisecond = sendDate.ToJalaliDateTimeMilisecond()

```





