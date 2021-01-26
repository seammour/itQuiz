```java
while (line != null) {
    //System.out.println(line);
    // read next line
    line = reader.readLine();
    if(line!= null) {
        if (map.containsKey(line) ) {
            map.put(line, 1);
        } else {
            map.put(line, map.get(line) + 1);
        }
    }
}
```
