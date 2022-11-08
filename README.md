# Java-word-count-beam. </br>
<ol><b>1. For checking maven version</b></br>
       mvn -v. </ol> <br>
<ol><b>2. For creating word count folder</b><br>
      mvn archetype:generate ` <br>
      -D archetypeGroupId=org.apache.beam ` <br>
      -D archetypeArtifactId=beam-sdks-java-maven-archetypes-examples ` <br>
      -D archetypeVersion=2.42.0 ` <br>
      -D groupId=org.example ` <br>
      -D artifactId=word-count-beam ` <br>
      -D version="0.1" ` <br>
      -D package=org.apache.beam.examples ` <br>
      -D interactiveMode=false </ol> <br>

<ol><b>3. For changing directory</b></br>
       cd .\word-count-beam </ol> <br>
       
<ol><b>4. To run a pipeline</b></br>
       mvn compile exec:java -D exec.mainClass=org.apache.beam.examples.WordCount ` <br>
       -D exec.args="--inputFile=sample.txt --output=counts" -P direct-runner</ol> <br>
       

<ol><b>5. For outputs</b></br>
       more counts*</ol> <br>

   
