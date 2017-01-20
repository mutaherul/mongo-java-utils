# mongo-java-utils

##  BasicBSONObjectBuilder ##
    * Package: mongo-java-utils/src/main/java/me/mutaherul/mongo/java/utils/BasicBSONObjectBuilder.java
    A builder for creating BasicBSONObject models from scratch.
    Utility for building complex BasicBSONObject.
    This builder provides methods to add name/value pairs to the object model and to return the resulting object.
    The methods in this class can be chained to add multiple name/value pairs to the object.
    This class does not allow null to be used as a name(key/field) while building the BasicBSON object

    
    * This class will be helpful to use with com.mongodb.hadoop.io.BSONWritable ( BSONWritable(BSONObject doc) )


