# Vinicius Ornelas

**Senior Full Stack Software Engineer** | Java/Spring backend focus | Brazil (Remote)

[LinkedIn](https://www.linkedin.com/in/vinicius-ornelas/) | [GitHub](https://github.com/OrnelasD-Rogers)

I work across the boundary between backend systems, data integrity, and clients that cannot always rely on a stable connection.

## Engineering shape

<table>
  <tr>
    <td valign="top" width="33%">
      <h3>Build</h3>
      Java 21<br>
      Spring Boot 3<br>
      REST APIs<br>
      PostgreSQL<br>
      Flyway<br>
      JPA and JDBC
    </td>
    <td valign="top" width="33%">
      <h3>Make it reliable</h3>
      Data modelling<br>
      Transactional writes<br>
      RBAC and JWT<br>
      SQLite persistence<br>
      Reverse sync<br>
      Integration tests
    </td>
    <td valign="top" width="33%">
      <h3>Operate</h3>
      Docker<br>
      GitHub Actions<br>
      GHCR<br>
      Tailscale/SSH deployment<br>
      Structured logs<br>
      Loki/Grafana
    </td>
  </tr>
</table>

## Selected system

### Eletroluk Workshop Management System

**Clients** -> **Java 21 / Spring Boot API** -> **PostgreSQL**

An independent production system used by five active repair-shop users. It replaced spreadsheet-based tracking with workflows for customers, service orders, quotes, repairs, and pickups.

Technical decisions I own in the system include:

- A hybrid persistence boundary: JPA for transactional writes and JDBC/PostgreSQL reads using LATERAL JOINs, `json_agg`, and `jsonb_build_object`.
- JWT RS256 validation with issuer/audience checks, refresh-token rotation and revocation, device-bound API keys, and administrative RBAC.
- Correlation IDs and structured HTTP logs, with Loki/Grafana configuration for investigation.
- Docker-based deployment through GitHub-hosted runners to a self-managed server using Tailscale/SSH.

**[Explore the repository](https://github.com/unspoken-tech-org/workshop_rest_api)**

## Where I have worked

**Yandeh**

Full-stack product work across a B2B catalogue platform: Java/Spring APIs, versioned PostgreSQL/Flyway migrations, React/TypeScript workflows, Node.js BFF aggregation, and Flutter mobile modules.

The work included association and audit data integrity, role-aware authorization, SQLite migration, connectivity-aware retry, reverse synchronization, mission workflows, and production bottleneck investigation with Dynatrace.

**Independent product work**

Design and operation of the Eletroluk system, from schema and API boundaries to security, observability, integration testing, and deployment.

## Current focus

Growing toward broader backend ownership while keeping a practical full-stack perspective. I am especially interested in Java/Spring systems, PostgreSQL, mobile reliability, integration testing, and AI-assisted engineering workflows.

## Open to

Remote roles from Brazil or relocation opportunities in the US and EU: Senior Full Stack Software Engineer, Senior Software Engineer, and Senior Java Backend Engineer.
