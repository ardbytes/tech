#### Current
* Book reading: Operating Systems in Three easy pieces
* [Transformers: Deep Dive](https://www.brandonrohrer.com/transformers#second_order_skips)
* [LLM from Scratch by Sebastian](https://github.com/rasbt/LLMs-from-scratch)
* [JSON optimazations by byroot](https://byroot.github.io/)
* [Linux Container in 500 lines](https://blog.lizzie.io/linux-containers-in-500-loc.html)
* [Building Query Compilers](https://pi3.informatik.uni-mannheim.de/~moer/querycompiler.pdf)

#### Routine

1. [Backend](/backend.md)

# 6-Week Ruby/Rails Blog Reading Schedule
**Start Date**: March 24, 2025  
**Notes**:  
- One blog per weekday, ~20-30 minutes daily.
- Covers all 16 blogs (13 original + Shopify, GitHub, Airbnb, Basecamp) with minimal repetition.

---

## Week 1: March 24 - March 28, 2025
- [Getting started with Rails](https://guides.rubyonrails.org/getting_started.html)
- **Monday, March 24**: *RubyGuides*  
  - **Focus**: Pick a Ruby fundamentals or metaprogramming post.  
- **Tuesday, March 25**: *thoughtbot Blog*
  - **Focus**: Explore a Rails testing or refactoring article.  
- **Wednesday, March 26**: *GoRails*  
  - **Focus**: Read a tutorial on a Rails feature (e.g., ActionCable).  
- **Thursday, March 27**: *Ruby Weekly*  
  - **Focus**: Skim the latest newsletter or the most recent one.

---

## Week 2: March 31 - April 4, 2025
- [Devops Server Management by milanm](https://github.com/milanm/DevOps-Roadmap?tab=readme-ov-file#5-learn-server-management)
- [Sustainable Dev Environments](https://devbox.computer/)
- - **Monday, March 31**: *SitePoint Ruby*  
  - **Focus**: Read about a Ruby design pattern or technique.
  - [Siami's blog: Rails asset pipeline, old and new](https://blog.siami.fr/rails-asset-pipeline-old-and-new)  
- **Tuesday, April 1**: *Ruby on Rails Official Blog*  
  - **Focus**: Catch up on the latest Rails release notes.
  - [Asset pipeline guide](https://guides.rubyonrails.org/asset_pipeline.html)
- **Wednesday, April 2**: *Drifting Ruby*  
  - **Focus**: Watch/read a short screencast on a Ruby trick.  
- **Thu-Fri, April 3, 4**: *BigBinary Blog*
  - **Focus**: Dive into a Rails 7+ feature explanation.
---

## Week 3: April 7 - April 11, 2025
- **Monday, April 7**: *[Testing Rails Applications](https://guides.rubyonrails.org/testing.html)*  
  - **Focus**: Read the article
- **Tuesday, April 8**: *Apache Server*
  - **Focus**: Read this [article](https://www.twaino.com/en/blog/website-creation/apache-server-2/).  
- **Wednesday, April 9**: *[Testing Rails Applications](https://guides.rubyonrails.org/testing.html)*  
  - **Focus**: Read the article. 
- **Thursday, April 10**: *Shopify Engineering Blog*
  - **Focus**: Read one from [this list](#shopify).
  - [Chapter 5: Testing Rails Applications](https://guides.rubyonrails.org/testing.html#functional-testing-for-controllers)  
- **Friday, April 11**: *GitHub Engineering Blog*  
  - **Focus**: Check a Ruby-related post or API development article.
  - Read [Sustainable Dev Environments](https://devbox.computer/)

---

## Week 4: April 14 - April 18, 2025
- [Securing Rails Applications](https://guides.rubyonrails.org/security.html)
- **Monday, April 14**: *Airbnb Engineering Blog*  
  - **Focus**: Read a Ruby or Rails backend engineering post.  
- **Tuesday, April 15**: *Basecamp Blog*  
  - **Focus**: Dive into a Ruby on Rails engineering post (e.g., scaling HEY).  
- **Wednesday, April 16**: *Shopify Engineering Blog*  
  - **Focus**: Read one from [this list](#shopify). 
- **Thursday, April 17**: *thoughtbot Blog*  
  - **Focus**: Check a Rails optimization or gem-related article.  
- **Friday, April 18**: *GoRails*  
  - **Focus**: Explore a deployment or API-related post.  

---

## Week 5: April 21 - April 25, 2025
- [Debugging Rails Applications](https://guides.rubyonrails.org/debugging_rails_applications.html)
- **Monday, April 21**: *Ruby Weekly*  
  - **Focus**: Review the latest issue for new links and trends.  
- **Tuesday, April 22**: *BigBinary Blog*  
  - **Focus**: Read about a Ruby or Rails under-the-hood topic.  
- **Wednesday, April 23**: *SitePoint Ruby*  
  - **Focus**: Pick an advanced Ruby technique article.  
- **Thursday, April 24**: *Drifting Ruby*  
  - **Focus**: Catch another quick Ruby/Rails tip or screencast.  
- **Friday, April 25**: *Read Sustainable Dev Environments*  
  - **Focus**: Explore a new tool or library comparison.  

---

## Week 6: April 28 - May 2, 2025
- **Monday, April 28**: *BigBinary Blog*
  - **Focus**: Read about a Ruby or Rails under-the-hood topic. 
- **Tuesday, April 29**: *Everyday Rails*  
  - **Focus**: Continue with testing or a practical Rails tip.  
- **Wednesday, April 30**: *Pat Shaughnessy*  
  - **Focus**: Read another internals post (e.g., memory management).  
- **Thursday, May 1**: *Avdi Grimm’s Blog*  
  - **Focus**: Explore a Ruby coding pattern or philosophy.  
- **Friday, May 2**: *Shopify Engineering Blog*  
  - **Focus**: Read one from [this list](#shopify).

---

### <a name="shopify"></a> Top 10 Rails-Specific Blog Posts from Shopify Engineering

Here’s a curated list of standout Rails-related posts from the [Shopify Engineering Blog](https://shopify.engineering/), blending performance, scalability, and practical Rails insights.

1. **["How to Write Fast Code in Ruby on Rails" (October 8, 2019)](https://shopify.engineering/how-to-write-fast-code-ruby-on-rails)**  
   - A guide to optimizing Rails performance with efficient Active Record queries, caching, and background jobs. Packed with practical examples for speeding up apps.

2. **["Dealing with Contention: How We Improved Rails Concurrency on MySQL" (October 25, 2018)](https://shopify.engineering/dealing-with-contention-how-we-improved-rails-concurrency-mysql)**  
   - Details Shopify’s fixes for database contention in Rails, improving concurrency and reducing lock wait timeouts on MySQL—a scalability gem.

3. **["Living on the Edge of Rails" (August 21, 2019)](https://shopify.engineering/living-edge-rails)**  
   - Explores Shopify’s bold choice to run Rails edge in production, managing weekly updates and contributing to the framework. A unique look at cutting-edge Rails usage.

4. **["Scaling Background Jobs at Shopify" (March 17, 2020)](https://shopify.engineering/scaling-background-jobs-shopify)**  
   - Covers how Shopify scales Sidekiq and Active Job to handle millions of jobs daily, with queue optimizations and worker tuning for Rails at scale.

5. **["Upgrading Shopify to Rails 5" (June 20, 2017)](https://shopify.engineering/upgrading-shopify-to-rails-5)**  
   - Chronicles the challenges and strategies of upgrading Shopify’s massive Rails monolith to Rails 5, offering lessons for large-scale migrations.

6. **["Shopify-Made Patterns in Our Rails Apps" (July 13, 2021)](https://shopify.engineering/shopify-made-patterns-our-rails-apps)**  
   - Highlights custom Rails patterns like podded sharding and maintenance tasks, showing how Shopify adapts Rails for their unique needs.

7. **["Shopify’s Flashback: Rewriting a Rails App From Scratch" (September 27, 2016)](https://shopify.engineering/shopify-flashback-rewriting-rails-app-scratch)**  
   - A case study on rewriting a Rails service for better performance, contrasting old and new approaches to tackle scalability bottlenecks.

8. **["Introducing the Merge Queue" (June 8, 2018)](https://shopify.engineering/introducing-the-merge-queue)**  
   - Explains Shopify’s merge queue for Rails deployments, solving concurrency issues in their CI/CD pipeline—a scalability enabler.

9. **["Load Balancing Rails at Scale" (November 15, 2017)](https://shopify.engineering/load-balancing-rails-scale)**  
   - Dives into load balancing Rails with HAProxy and middleware, ensuring responsiveness during traffic surges like Black Friday.

10. **["Hotwire for Rails at Shopify Scale" (December 14, 2022)](https://shopify.engineering/hotwire-for-rails-at-shopify-scale)**  
    - Showcases Shopify’s use of Hotwire (Turbo and Stimulus) to enhance Rails apps with dynamic, real-time features at massive scale.

This list offers a mix of technical depth—code snippets, metrics, and architectural insights—making it a valuable resource for Rails developers looking to level up.

---

## Tips for Success
- **Bookmark Favorites**: Save standout articles for reference.  
- **Adjust as Needed**: Swap blogs if content feels too basic/advanced.  
- **Engage**: Comment on posts or share on X to connect with the community.  
- **Track Progress**: Note one key takeaway daily to reinforce learning.  

**Next Steps**: After Week 6, repeat the cycle, shuffling the order or exploring archives. Adjust start date as needed.
