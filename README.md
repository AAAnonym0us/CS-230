# CS-230
# Journal entry

**Summary of the Client and Requirements**

The client was The Gaming Room, a company that originally developed their game Draw It or Lose It for Android devices. They wanted to expand the game into a web-based, cross-platform application that could run on multiple environments (Linux, macOS, Windows, and mobile devices). The key requirements included supporting multi-user functionality, managing games, teams, and players uniquely, and ensuring scalability and security for thousands of concurrent users.

**What I Did Well**

I feel that I did particularly well in clearly evaluating and comparing the strengths and weaknesses of different platforms. My documentation showed the client how Linux, Windows, Mac, and cloud-based environments each stacked up in terms of server-side hosting, client-side compatibility, and development tools. I also think I succeeded in making my recommendations clear and actionable, so the client could see why a cloud-based Linux environment would give them the best scalability and cost-effectiveness.

**Helpful Parts of the Design Process**

Working through the design document made it much easier to approach the coding side of the project. For example, documenting the Singleton and Iterator design patterns in advance clarified how I should structure my GameService and enforce unique names for games, teams, and players. The process forced me to think ahead about architecture, constraints, and scalability before jumping into code.

**What I Would Revise**

If I had the chance to revise one part of my work, it would be the Recommendations section. I would expand even further on distributed architectures, especially comparing serverless and microservices approaches. While my document touched on these ideas, I think adding a deeper dive would strengthen the future-proofing of the design.

**Interpreting User Needs**

I translated the client’s needs by focusing on usability, scalability, and security. For example, they needed thousands of players supported at once, so I prioritized scalability in the evaluation and recommended cloud-based deployment. They needed unique names for games and teams, so I used an iterator-based check in the code. Considering user needs is critical because if the software doesn’t align with real-world expectations, adoption and success will suffer, no matter how well it’s coded.

**Approach to Software Design**

I approached the design using a combination of structured documentation and object-oriented principles. The techniques that worked well for me included:

  - Using design patterns (Singleton, Iterator) to enforce constraints.
  - Documenting business and technical requirements separately for clarity.
  - Comparing platforms in a structured evaluation matrix to help with decision-making.
  - Keeping security in mind from the start with authentication and role-based access.

In the future, I would continue to use these strategies, but also incorporate more agile feedback cycles, refining the design as I gather more input from clients and developers. This iterative approach would help balance technical feasibility with client priorities even more effectively.
