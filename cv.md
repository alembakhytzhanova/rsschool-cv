# Alem Bakhytzhanova

---

### Contact Information
- **Email**: florangorr@gmail.com
- **GitHub**: [alembakhytzhanova](https://github.com/alembakhytzhanova)
- **LinkedIn**: [linkedin.com/in/alembakhytzhanova](https://linkedin.com/in/alembakhytzhanova)

---

### Summary
Aspiring Junior Developer with a passion for continuous learning and skill-building. Eager to contribute to a team where I can leverage my knowledge in backend development and problem-solving skills, while continuously improving and expanding my skill set. I am proactive and thrive in environments that encourage self-learning and exploration of new technologies. My goal is to grow into a strong developer capable of delivering efficient, high-quality code.

---

### Skills
- **Languages**: Go, SQL, HTML, CSS
- **Frameworks**: Basic REST API development
- **Version Control**: Git, GitHub
- **Tools**: Docker, Visual Studio Code, PostgreSQL, SQLite
- **Methodologies**: Agile, Scrum

---

### Code Examples
#### Latest Code Example
Here’s a sample solution to a coding challenge from LeetCode called "Two Sum" (in Go):

```go
// Problem: Find indices of the two numbers that add up to a specific target.
func twoSum(nums []int, target int) []int {
    indices := make(map[int]int)
    for i, num := range nums {
        complement := target - num
        if index, found := indices[complement]; found {
            return []int{index, i}
        }
        indices[num] = i
    }
    return nil
}

## Certifications

- **Frontend Development** by [freeCodeCamp](https://freecodecamp.org) - July 2023
- **Backend Development with Go** by [Coursera](https://coursera.org) - May 2023
- **HTML & CSS for Beginners** by [Codecademy](https://codecademy.com) - January 2023

