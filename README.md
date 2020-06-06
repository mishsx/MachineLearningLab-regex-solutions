# MachineLearningLab-regex-solutions
My regex solutions to 12 level challenge with F-Measure 100 at each level. 

* ## Level 1
` \d+`

* ## Level 2
` (?:[a-z0-9]{2}:){5}(?:[a-z0-9]{2})`

* ## Level 3
` ftp://ftp(?:[0-9]{1,2})?\.(?:[a-z]{2}\.)?(?:FreeBSD.org/pub/FreeBSD/)`

* ## Level 4
` \$.+?\$`

* ## Level 5
` (25[0-5]|2[0-4][0-9]|[01]?[0-9][0-9]?)\.(25[0-5]|2[0-4][0-9]|[01]?[0-9][0-9]?)\.(25[0-5]|2[0-4][0-9]|[01]?[0-9][0-9]?)\.(25[0-5]|2[0-4][0-9]|[01]?[0-9][0-9]?)`

* ## Level 6
` href=('|").+?\1`

* ## Level 7
` http://[A-Za-z\d\.?=&/~_;:-]+[\da-z/]`

* ## Level 8
` <([a-z]\d).*?[^>]?>.+<\/\1>`

* ## Level 9
` \(?\d{3}[\)\-/.]? ?\d{3}[\)\-.]?\d{4}`

* ## Level 10
`(?<=({| ))[A-Z][A-Za-z\-]+, [A-Z]([^\s]+)? ?([A-Z][a-z]+)?[A-Z]?\b(?<!\s)`

* ## Level 11
` (?<=(<h\d.*>)).+(?=<)` 

* ## Level 12
`((?<=^\d\d?\d?\. )\w+, ([A-Z\.]+){1,2}`
