# Metrics for Effective Teams

## Execution

- **DORA** ([article](https://cloud.google.com/blog/products/devops-sre/using-the-four-keys-to-measure-your-devops-performance)):
   - Deployment freq,
   - Lead time,
   - Failure rate,
   - MTTR.

- [SPACE](https://queue.acm.org/detail.cfm?id=3454124):

   - *Satisfaction* and well-being;
   - *Performance* is the outcome of a system or process;
   - *Activity* is a count of actions or outputs completed in the course of performing work;
   - *Communication and collaboration* capture how people and teams communicate and work together;
   - *Efficiency and flow* capture the ability to complete work or make progress on it with minimal interruptions or delays, whether individually or through a system.

<!--
At the current iteration (tech < 20 engineers), no issues with quality, focus on flow of delivery:
Deployment Frequency:
production
      I track the whole system (as the primary  KPI) and per component (supportive, to have it for detailed discussions or as data for the retrospective).
Mean Lead Time for Change - from opening PR as a draft, in our company, we open such a PR as a very first step. Ar our scale, it is sufficient.
Change Failure Rate - I do not track it precisely; I update a Google Spreadsheet/Google Notebook when it happens.
Mean Time to Recovery - I consider only incidents P1 and P2.
On which metrics you focus first, it depends on the size of your engineering and your current challenges.
I bring at the 1on1 and retros DF and Lead Time; there were a few times when we talked about CFR.
-->

## Work mgmt

- Kanban - aging tasks first, before anything more complex, reducing WIP (see [Fixing Your Kanban](https://www.youtube.com/watch?v=ZP2NOy0EBgI&list=PL9uyGDiy_ChVfUxjc5gowNg0wW0gLFnx6)),
- Scrum - weekly, the process own by the team.

## References

- [Measuring an engineering org](https://lethain.com/measuring-engineering-organizations/)
- [DevOps Handbook](https://www.amazon.com/DevOps-Handbook-World-Class-Reliability-Organizations/dp/1942788002);
- Kanban:

  - [Kanban Guide](https://prokanban.org/the-kanban-guide/),
  - [Daniel Vacanti's talks from on Kanban](https://www.youtube.com/watch?v=689kYrWGqfE) (seria [Fixing Your Kanban](https://www.youtube.com/watch?v=ZP2NOy0EBgI&list=PL9uyGDiy_ChVfUxjc5gowNg0wW0gLFnx6) jest dobrym startem),
  - https://www.crisp.se/gratis-material-och-guider/kanban.

- Scrum:

  - **zacznij od poznania początków**, żeby uniknąć wypaczonego Scrum: [Jeff Sutherland on scrum](https://www.youtube.com/watch?v=O7cA1q0XwhE), [Jeff Sutherland google talk](https://www.youtube.com/watch?v=M1q6b9JI2Wc), [Robert C. Martin](https://www.youtube.com/watch?v=hG4LH6P8Syk), i [Ken Schwaber](https://www.youtube.com/watch?v=IyNPeTn8fpo),
  - [Scrum guide](https://www.scrum.org/resources/scrum-guide).

- [Scrum + Kanban from Trenches](https://www.infoq.com/minibooks/scrum-xp-from-the-trenches-2/);
- ShapeUp (tutaj nie mam doświadczenia) - https://basecamp.com/shapeup;
- Świetne źródło inspiracji - https://blog.crisp.se/.
