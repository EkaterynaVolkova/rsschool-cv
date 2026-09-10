# Ekaterina Volkova
![avatar](/img/myavatar.jpg )


## Contact Information
**Discord:** katev.code  
**Email:** volkova5005@gmail.com  
**GitHub:** [EkaterynaVolkova](https://github.com/EkaterynaVolkova)  
**Location:** Burgas, Bulgaria

## Summary
**Goal & Motivation:** Highly motivated and dedicated developer currently restarting my studies at RS School to strengthen my core technical foundation and transition into modern frontend development.  
**Strengths:** Quick learner with a strong analytical mindset, detail-oriented, and passionate about writing clean, maintainable code.  
**Experience & Growth:** Brings valuable commercial background in backend development, combined with a strong eagerness to master modern JavaScript/TypeScript ecosystems and build user-centric web applications.

## Skills
**Programming Languages:** PHP, JavaScript, TypeScript (basic/learning)  
**Backend & CMS:** Drupal, WordPress, MySQL  
**Version Control & Tools:** Git, GitHub, Composer, Docker  
**Methodologies:** Agile, Basic CI/CD

## Code Examples
Given some integer, find the maximal number you can obtain by deleting exactly one digit of the given number.
```
function deleteDigit(n) {
  let str = n.toString();
  let res = 0;
  let new_str;
  for(let i = 0; i < str.length; i++) {
    new_str = str.slice(0, i) + str.slice(i + 1);
    if (Number(new_str) > res) {
      res = Number(new_str);
    }
  }
  return res;
}
```

## Work Experience
**PHP (Drupal) Backend Developer** | Web4pro (Present)

## Education
* **RS-School JS Frontend Courses** (2025)
* **A-Level PHP Courses** (2018)

## Languages
**English:** Intermediate (B1+)