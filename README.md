```go
type Engineer struct {
    Name      string
    Role      string
    Location  string
    Language  string
    Passion   []string
}

func main() {
    me := Engineer{
        Name:     "Qaiser Abbasi",
        Role:     "Cloud Platform Architect & Tech Lead",
        Location: "Berlin",
        Language: "Php",
        Passion:  []string{"Scaling Systems", "DevOps", "Mentoring"},
    }
    
    // 12+ years of experience delivering for:
    // SoundCloud, AboutYou, SAP, RTL, Delivery Hero
    
    me.BuildReliableSystems()
}
