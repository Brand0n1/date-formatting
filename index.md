## Date Formatting

When formatting a date there is multiple diffrent patterns you can use. You can found out more about this by reading the [Java docs by Oracle]( https://docs.oracle.com/javase/7/docs/api/java/text/SimpleDateFormat.html).

### Region formatting
If you are looking for just area specifc formatting then this section will be valuable to you.
- In the USA time is formatted like this `MM-dd-yyyy`
- In China, Japan, Korea, and Iran the date is often formatted like this `yyyy-MM-dd`
- In most other countries in the world the date is formatted like this `dd-MM-yyyy`

__Region specific data was gathered from [mit.edu](https://iso.mit.edu/americanisms/date-format-in-the-united-states/)__

### Understanding the different components of date formatting
Lets start off by saying that the dashes `-` don't have anything to do with the actual formatting, and are just added in so it reads nicer.

The `MM` seen in all of these date formats is capitolized because when dealing with dates in java the lowercase counterpart `mm` will get minutes.
`MM` will return the month of the year based on whatever was entered into the date formater. Doing one `M` will result in just the month appearing while doing `MMM` will return the written shorthand of the month. `MMMM` will return the full name of the month.

The `dd` is the current day of the month based on whatever was entered into the date formater. We use lowercase `dd` in this situation because the upercase version will result in getting the current day of the year rather than month, throwing off the date.

The `yyyy` is the current year based on whatever was entered into the date formater. We use lowercase to get the calender year rather than the week year.


### Pages
- [Home Page](https://brand0n1.github.io/)
- [Mob List (SpawnerShards)](https://brand0n1.github.io/minecraft-mob-list/)
- [Date Formatting](https://brand0n1.github.io/date-formatting/)
- [Time Formatting](https://brand0n1.github.io/time-formatting/)
