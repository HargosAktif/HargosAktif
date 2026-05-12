<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:000000,100:8b0000&height=180&section=header&text=LaXenT%20%2F%20LatenT&fontSize=60&fontColor=ffffff&fontAlignY=38&desc=Security%20Research%20%7C%20Learning%20Phase%20%7C%20Terminal%20Driven&descAlignY=62&descSize=18&animation=fadeIn" width="100%"/>
</div>
class LatenT:
    def __init__(self):
        self.name = "Miraç"
        self.aliases = ["LatenT", "LaXenT"]
        self.age = 15
        self.location = "Turkey 🇹🇷"

        self.status = "Security Researcher (Learning Phase)"

        self.focus_areas = [
            "Offensive Security",
            "Network Security & Reconnaissance",
            "Web Application Security",
            "Security Tool Development",
            "Automation & Scripting"
        ]

        self.skills_in_progress = {
            "Linux": "Kali / Ubuntu daily usage",
            "Python": "Security tools & automation",
            "Burp Suite": "Web testing workflow",
            "Nmap": "Network enumeration practice",
            "Go / C#": "Tool development (basic-intermediate)"
        }

        self.interests = [
            "Vulnerability research",
            "CTF challenges",
            "Pentesting labs (TryHackMe / HackTheBox)",
            "System internals"
        ]

        self.tools = [
            "Nmap",
            "Wireshark",
            "Burp Suite",
            "Metasploit (learning)",
            "SQLMap",
            "Aircrack-ng"
        ]

        self.motto = "Understand systems, don't just use tools"

    def mindset(self):
        return "Learn → Break → Analyze → Improve"

    def __str__(self):
        return f"{self.aliases[0]} | Security Researcher in progress"
