```go
package person

type Person struct {
	Name         string
	Age          int
	Pronouns     []string
	Education    string
	CurrentFocus string
	Curiosities  []string
	FunFact      string
}

func NewPerson() *Person {
	return &Person{
		Name:         "João Guilherme dos Santos",
		Age:          21,
		Pronouns:     []string{"he", "she", "they"},
		Education:    "In the 6th semester of software engineering",
		CurrentFocus: "Learning CS and Golang",
		Curiosities:  []string{"I'm fascinated by high performance and low latency systems and how they work", "I'm a Linux enthusiast", "I prefer to use TUIs and CLIs instead of GUIs", "I hate writing React for more than 1 hour"},
		FunFact:      "Cats are my favourite animals",
	}
}
```
