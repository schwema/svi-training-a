##Newsletter Parser Work Plan

1. Write a python script to scrape contents of newsletters. This can be done by connecting to the **IMAP4** server of the domain.

2. Using **Natural Language Processing**:
	*	Write PythonParse email contents using beautifulsoup or scrapy for the parts written in **HTML** and **Regex** for those that are not.
	*	Sort email contents depending on category, e.g. events, android, python, etc.

3. Create bespoke newsletter templates depending on the field of expertise of the user. This will be created using a python template engine like **Jinja**. e.g. To Clau, as she specializes on android, The first entries on her newsletter will be news about android.

4. Write a python script that will automatically send these newsletter to users. This can be done through connecting to the **SMTP** of a mail server using **MIME** (Multi-Purpose Internet Mail Extensions).
