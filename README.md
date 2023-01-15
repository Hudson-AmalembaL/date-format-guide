# date-format-guide
## Dates Format

1. 2001-07-04T12:08:54+03:00    `{moment("20010704T120854").format()}`
2. July 4th 2001    `{moment("20010704T120854").format("MMMM Do YYYY")}{" "}` 
3. Wednesday    `{moment("20010704T120854").format("dddd")}`
4. Jul 4th 01   `{moment("20010704T120854").format("MMM Do YY")}{" "}`
5. 2001   `{moment("20010704T120854").format("YYYY")}`
6. July     `{moment("20010704T120854").format("MMMM")}`
7. 4th    `{moment("20010704T120854").format("Do")}`
8. 4    `{moment("20010704T120854").format("D")}`
9. Wed    `{moment("20010704T120854").format("ddd")}`
10. 2001    `{moment("20010704T120854").format("YYYY")}`
11. Mon   `{moment("July 20 2020").format("ddd")}`
12. Monday    `{moment("July 20 2020").format("dddd")}`
13. 20    `{moment("20 July 2020").format("D")}`
14. Wednesday   `{moment("2006-07-05").format("dddd")}`
15. June 4th 2001, 12:09:56 pm `{moment("June 04 2001@12:09:56").format("MMMM Do YYYY, h:mm:ss a")}{" "}`

## For local formats
1. 12:08 PM   `{moment("20010704T120854").format("LT")}`
2. 12:08:54 PM    `{moment("20010704T120854").format("LTS")}`
3. 07/04/2001   `{moment("20010704T120854").format("L")}`
4. 7/4/2001   `{moment("20010704T120854").format("l")}`
5. July 4, 2001   `{moment("20010704T120854").format("LL")}`
6. Jul 4, 2001    `{moment("20010704T120854").format("ll")}`
7. July 4, 2001 12:08 PM    `{moment("20010704T120854").format("LLL")}`
8. Jul 4, 2001 12:08 PM   `{moment("20010704T120854").format("lll")}`
9. Wednesday, July 4, 2001 12:08 PM   `{moment("20010704T120854").format("LLLL")}`
10. Wed, Jul 4, 2001 12:08 PM   `{moment("20010704T120854").format("llll")}`

## Calendar Time</h2>
1. 06/24/2001 =  `{moment("20010704T120854").subtract(10, "days").calendar()}{" "}`
2. 07/04/2001   `{moment("20010704T120854").calendar()}`
3. 07/07/2001   `{moment("20010704T120854").add(3, "days").calendar()}{" "}`

## Relative Time
1. 22 years ago   `{moment("20010704T120854").fromNow()}`
