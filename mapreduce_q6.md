```scala
def average(values: Iterator[Double]): Option[Double] = {
    if(values.size == 0){
        None
    }
    else {
        val si = values.size
        val s = values.sum
        Some(s/si)
    }
}
```

