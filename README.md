# saas-startup-cto-checklist
A checklist of all things to consider for CTOs of SaaS startups.

### Who is this for?
The first CTO, engineer, cofounder of a pre-seed startup who is accountable for building the SaaS app.

### Before you start
- [ ] Choose the boring technology
  - https://mcfunley.com/choose-boring-technology
- [ ] Have an opinion/a point of view in how you plan to work along with what you plan to work on
  - https://rubyonrails.org/doctrine/

### Tools
- [ ] GitHub 
- [ ] Pick a Platform as a Service/cloud computing that you are most comfortable with
- [ ] Have a CDN instead for providing assets from your webserver
- [ ] Start a wiki (use GitHub for it)
- [ ] Setup Continuous Integration (CI)

### Architecture
- [ ] Pick a lane
  - Server Side Rendering v/s Client Side Rendering
  - Monolith vs Microservices
- [ ] Pick a framework that you are most comfortable with
- [ ] User authorization and policy-based access
- [ ] "Admin" User
- [ ] When setting up data models, think about teams/groups that you will eventually need to support
- [ ] You will likely need to support subdomains in the future
- [ ] Where will your marketing site and company blog run
  - If your marketing site is built within your app, you will become the bottleneck for growth/marketing
  - Having your app running on app.yourdomain.com from day 1 might make it easier to switch later
- [ ] Evenutally you will need to provide an API

### Code
- [ ] Adapt a style guide from day 1
- [ ] Start adding spec tests from day 1
- [ ] Decide on comments or no comments in code
- [ ] Use linters to help standarize code as well as make code reviews better for everyone
- [ ] Set and document guidelines and best practices for logging
- [ ] Set and document guidelines and best pracitces for exception handling
- [ ] Set up runtime errors and exception reporting
- [ ] Set up realtime analytics for performance reporting
- [ ] Set up ability to track changes to your records at database level for auditing or versioning
- [ ] Define and document process and expectations for code reviews
  - https://mtlynch.io/human-code-reviews-1/
  - https://mtlynch.io/human-code-reviews-2/
  
### Engineering Team
- [ ] Always be looking forward and "recruiting"
- [ ] Once you have at least one more engineer, define engineering levels 
- [ ] Set up a structure to allow for experimentation
- [ ] QA: You will need QA earlier than you think you do
- [ ] When you are no longer effective managing the team, look for a Manager/Director/VP of Engineering who is 10x better than you

### Day-to-day execution
- [ ] stand-ups, sprints, retros, milestones
- [ ] Use simple "project management" to keep a healthy product development rhythm, no matter how small your "team"

### Product
- [ ] Use "feature flags" to release new features and selectively enable them for existing customers.
- [ ] Don't make the thing more awesome, always look for how to make your users more awesome
- [ ] To make a decision, look for answers in analytics and metrics
- [ ] Reporting: Sooner or later, the data you can query from the database will need to be turned into reporting features for your customers

### Support
- [ ] Have an Admin interface from day 1
- [ ] To ensure the "health" of your application, set up a status page
- [ ] Provide an "impersonate" feature to Admins to help experience what the customers are experiencing

### Security
- [ ] Go through the SaaS CTO Security Checklist
  - https://www.sqreen.com/checklists/saas-cto-security-checklist
- [ ] Prepare a set of assets to share with Enterprise customers
- [ ] Run static code analysis security tool for your frameworks
- [ ] Look into a third-party pen testing and code audit service/tool sooner than you think you will need to

### Compliance
- [ ] Get familiar with the top 3 compliance standards in your industry
- [ ] Create a skeleton of what it would take your company to get the top 3 compliance certificates in your industry

### Others/work-life-balance
- [ ] Find a way to mentor someone (within or outside your company)
- [ ] Join a community of CTOs, engineers, technical leaders who you can knowledge share with
- [ ] In your day-to-day, balance big projects and small enhancements/bug fixes 



