message = "Databricks was developed by the same team who originally developed Spark. Databricks is Spark on cloud. It makes spark programminh easy"
word="Databricks"
#find()
print(message.find(word))

name="kaizen"
print(message.find(name))

print(message.count(word))



message = "Databricks was developed by the same team who originally developed Spark. batabricks is Spark on cloud. It makes spark programminh easy"
word1="Spark"
print(message.count(word1))


##upper,Lower case

message2 = "Databricks was developed by the same team who originally developed Spark. batabricks is Spark on cloud. It makes spark programminh easy"

print(message2.lower())
print(message2.upper())

--
message2 = "Databricks was developed by the same team who originally developed Spark. batabricks is Spark on cloud. It makes spark programminh easy"
word1="Spark"

print(message2.lower().count(word1.lower()))
print(message2.upper().count(word1.upper()))
--

spark="Apache Spark is a powerful, open-source, unified analytics engine designed for large-scale data processing.its speed and scalability, making it a popular choice for various big data applications like batch and real-time data analytics, machine learning, and AI. Spark can process data much faster than traditional methods like Hadoop, often 10 to 100 times faster"
print(spark[0])

print(spark[len(spark)-])

print(spark[3:10])

lenthofstring="hello"
print(len(lenthofstring))

print(lenthofstring[4])

print(lenthofstring[len(lenthofstring)-1])
