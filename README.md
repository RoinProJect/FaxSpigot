
Compile From Source
-> {
      clone this repo;
      
      if(success) {
          continue;
      }
      
      run ./gradlew applyPatches
      run ./gradlew decompileJar
      
      -> now build jar
      
      ./gradlew createReobfBundlerJar
      
      the file will be located at "build/libs"
      
}
