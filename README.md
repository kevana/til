# til

## Groovy

### Profile closures
```
def profile = { closure ->  
  def start = System.currentTimeMillis()  
  closure.call()  
  def now = System.currentTimeMillis()  
  println "Elapsed time: ${now - start}"
} 
```
