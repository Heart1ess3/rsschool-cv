# Daniil Kirulay
![my photo](../rsschool-cv/img/my%20photo.jpg)

## Junior Front-end Developer

### Skills
- HTML CSS
- JavaScript (Basic)
- C#
- Java
- Figma
- Github

---
### Education

- Secondary education until 2022
- Belarusian-Russian Univercity , start at 2022, Bachelor degree
- B1; Good at grammar , but poor speaking skills

---
### Something about me

- Active Lifestyle
- In back i am professioanl skier
- Now getting ready to be a professional bodyduilder
- Funny and a little bit whimsical guy
- Good at math and all sorts of tasks

---
### Code Example
     ```csharp
        static void SearchTheCheapest()
        {
            //Console.WriteLine(TireArray.OrderBy((tire) => tire.price).FirstOrDefault().ToInput());
            int minPrice = TireArray.Min(tire => tire.price);
            var mostExpensiveTires = TireArray.Where(tire => tire.price == minPrice)
                                              .OrderByDescending(tire => tire.price);

            foreach (var tire in mostExpensiveTires)
            {
                Console.WriteLine(tire.ToInput());
            }
        }
        ```

---
### Contacts
- [instagram](https://www.instagram.com/heart1ess3/)
- tok220vtut@gmail.com
---