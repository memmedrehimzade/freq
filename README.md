# frequest
This is go CLI tool for send fast Multiple  get HTTP request.

# How to Use?
you can use this tool for findings xss and sql injection vulnerablity from multi URL.
example :  waybackurls redacted.tld | gf xss | qsreplace '"><img src=x onerror=alert(1);>' | freq 

# How to Install?
go get -u github.com/memmedrehimzade/freq


# smart Use
Using qsreplace you can add your xss payload in every perementer then you can use this tool to find vulnerablity.
