# AI Lead Generation Agent

I built this project to experiment with a simple question:

**Can I automate the boring part of lead generation without losing the quality of the leads?**

For the first test, I focused on restaurants in a specific area. Instead of manually searching through businesses one by one, I created an n8n workflow that collects businesses, analyzes the information, and decides which ones are actually worth reaching out to.

The first run collected around **20 businesses**.

After the AI qualification step, only **3 businesses** matched the criteria I had set.

Those qualified leads were then automatically added to **Google Sheets**, where they could be used for the next step of the process — personalized outreach.

### How it works

**Find businesses → Collect information → AI qualification → Filter leads → Google Sheets → Personalized outreach**

The part I found most interesting was the qualification step.

Getting a list of 20 businesses isn't particularly difficult. The more useful part is figuring out **which businesses are actually worth spending time on**.

That's what I wanted to test with this project.

### Tools I used

* **n8n** — to build and connect the workflow
* **Apify** — for business data collection
* **AI / LLM** — to analyze and qualify businesses
* **Google Sheets** — to store the qualified leads
* **APIs & Webhooks** — to connect the different parts of the workflow

### What you'll find here

The repository includes the exported n8n workflow, screenshots of the workflow and results, and sample data to make the project easier to understand.

API keys, credentials, and private information are not included.

### The result

**20 businesses → 3 qualified leads → Google Sheets → personalized outreach**

The goal wasn't simply to collect more businesses.

It was to build a workflow that could take a larger list, remove the noise, and leave behind leads that were more relevant for outreach.

If you're interested in AI automation, n8n, or lead generation workflows, feel free to explore the workflow and see how the different pieces are connected.
