## Functional Requirements
- The company is a startup and is limited with its finances. They would like to make the best use of open sourced LLMs. Thy would like to focus on teaching lesser known and translated languages such as constructed languages and indigenous languages. 

- To start with this venture they will be working with Toki Pona to observe customer engagement.


## Assumptions
- We are choosing models with 7B parameters to accomodate the company's existing infrastructure on their local servers.

- Assuming we will be able to provide services to nearest clientele, which is approximately 5-10 students. 

- Post successful trials, they will be hosting the application using cloud services and more extensive LLMs with the highest parameters.


## Data Strategy
- According to the Reddit Toki Pona community, [Toki Pona is not copyrighted](https://www.reddit.com/r/tokipona/comments/nscn05/is_toki_pona_a_copyrighted_or_can_people_use_it/). Hence, there shall not rise any copyright issues. We can freely use the data sources and store them in our database. 

- The current data sources are:
  - [Official Toki Pona website](https://tokipona.org)
  - [Toki Pona Dictionary](https://lipu-sona.pona.la/en/dictionary/)
  - [Unofficial Toki Pona Website](https://jan-ne.github.io/tp/)

- Data will be crawled or accessed using available APIs if any. 
- Data will be processed and ingested to the GenAI models and the VectorDB to provide personalised experiences and feedback to the Teachers and Students.


## Considerations
- Toki Pona is limited to a small community since it is a constructed language.
- Hence, translation is not completely error-free since the company does not have any Toki Pona specialist yet.
