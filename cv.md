
# Iryna Lytvynenko

### Junior Frontend Developer

---

### Contact information

**Phone:** +380 99 270 65 89 (UA), +375 29 854 16 79 (BY)

**E-mail:** w.iryna.lytvynenko@gmail.com

**Telegram:** @irroar

[Discord](https://discordapp.com/users/229632464748806145)

---

### About me

Stress-resistant, knows how to devote a lot of time to learning new technologies and processing new information. 
I approach the search for solutions to problems responsibly. 
I am fluent enough in English to read the technical documentation. 
I know how to communicate with the team during the development process, and I also had a little experience using Scrum.

---

### Skills

* HTML5, CSS3
* Javascript Basics
* Git
* SQL

---

### Code example
*Function for making query to get data from Zendesk API with Basic Authorization*

```
async function query(q, page, domain, token, apiAdress) {
    let url = new URL(domain + apiAdress);
    let params = [['query', q], ['page', page]];

    url.search = new URLSearchParams(params).toString();
    let headers = new fetch.Headers();
    headers.append('Authorization', 'Basic ' + token);
    try {
        let response = await fetch(url, {
            headers: headers,
        });
        return await response.json();
    }
    catch (e)
    {
        writeEvents(e + '\nQuery to zendesk was failed.\n', 'exceptions')
        return 'Error';
    }
}
```

---

### Experience

Sakrament IT, Minsk (August 2015 - May 2016) - Front-end Developer: creating CSS/SASS styles for school electronic textbooks + proofreading.

---

### Education

* **Nova Kakhovka Instrument Making College** - Software Development (Junior Specialist)
* **Belarusian State University of Informatics and Radioelectronics**, Faculty of Computer Systems and Networks (3 years)

---

### Languages
* Russian - Native
* Ukrainian - Native
* English - Upper Intermediate (according to the EF SET online test)
![](https://cdn.efset.org/efset-widget/img/certificate_59.png)
