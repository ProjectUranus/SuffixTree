# Suffix Tree

[mezz's](https://github.com/mezz/JustEnoughItems/tree/1.12/src/main/java/mezz/jei/suffixtree) modified version of [Generalized Suffix Tree](https://github.com/abahgat/suffixtree). Published for convenient use.

## Usage

```groovy
dependencies {
    // https://mvnrepository.com/artifact/com.projecturanus/suffixtree
    implementation 'com.projecturanus:suffixtree:1.0'
}
```

```java
import com.projecturanus.suffixtree.GeneralizedSuffixTree;

var tree = new GeneralizedSuffixTree();
tree.put(0, "java");
tree.put(1, "groovy");
tree.put(2, "kotlin");

tree.search("blabla"); // Returns a set of indices that were defined previously
```

## License

Apache-2.0
