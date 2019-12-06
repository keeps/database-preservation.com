---
layout: blocks
title: DBPTK
date: 2019-11-29T23:00:00.000+00:00
baseurl: https://www.database-preservation.com
page_sections:
- template: navigation-header-w-button
  block: header-2
  logo: "/uploads/2019/11/28/KEEPS_keeps_logo_black_en_vector.svg"
  navigation:
  - link: "#desktop"
    link_text: Desktop
  - link: "#enterprise"
    link_text: Enterprise
  - link: "#developer"
    link_text: Developer
  cta:
    url: "#download"
    button_text: Download
- template: hero-banner-w-image
  block: hero-2
  slug: dbptk
  headline: DBPTK <br><strong>Database Preservation Toolkit</strong>
  content: The tools to archive relational databases by saving all content into a
    specialized preservation format.
  cta:
    enabled: false
    url: "#download"
    button_text: Download now
  image:
    image: "/uploads/2019/10/07/dbptk_vertical_white_small_notitle.png"
    alt_text: DBPTK
  background_image: "/uploads/2018/06/21/hero-2-bg.png"
- template: 3-column-text-image
  block: three-column-image-1
  slug: download
  col_1:
    image: "/icons/black/svg/009-computer.svg"
    headline: Desktop
    content: Desktop application to save database to archival format, validate it
      and browse the content.<br><br><a class="button primary" href="https://github.com/keeps/db-visualization-toolkit/releases/latest"
      title="DBPTK Desktop download for Windows, MacOS or Linux">Download</a>
  col_2:
    image: "/icons/black/svg/012-cluster.svg"
    headline: Enterprise
    content: Web application to browse and search on the content of multiple large
      preserved databases.<br><br><a class="button primary" href="https://github.com/keeps/db-visualization-toolkit-docker#database-preservation-toolkit-enterprise-deploy-as-docker"
      title="DBPTK Enterprise docker install instructions">Read more</a> or <a class="button
      primary" href="mailto:sales@keep.pt?subject=DBPTK Enterprise installation service
      request" title="DBPTK Enterprise install service">Contact us</a>
  col_3:
    image: "/icons/black/svg/013-algorithm.svg"
    headline: Developer
    content: A command-line tool and development library for automation and system
      integration.<br><br><a class="button primary" href="https://github.com/keeps/db-preservation-toolkit#how-to-use"
      title="DBPTK Developer how to use instructions">Read more</a> or <a class="button
      primary" href="mailto:sales@keep.pt?subject=DBPTK Enterprise installation service
      request" title="DBPTK custom development service">Contact us</a>
- template: hero-banner-w-image
  block: hero-2
  slug: desktop
  headline: DBPTK Desktop
  content: Desktop application to save database to preservation format, validate it,
    and browse and search the content
  image:
    image: "/icons/white/svg/009-computer.svg"
    alt_text: ''
  background_image: ''
  cta:
    enabled: true
    url: https://github.com/keeps/db-visualization-toolkit/releases/latest
    button_text: Download for Windows, MacOS or Linux
- template: content-feature
  block: feature-1
  media_alignment: Right
  headline: "<strong>SIARD creation</strong><br>Export database to a preservation
    format"
  content: Connect to a local or remote database and save all content into a preservation
    format like SIARD.
  media:
    image: "/uploads/2019/11/29/dbptk-desktop-dbms-list.png"
    alt_text: DBPTK Desktop
- template: content-feature
  block: feature-1
  media_alignment: Left
  headline: "<strong>SIARD validation<br></strong>Validate archived database"
  content: Validate SIARD against specification plus many additional checks for a
    thorough validation.
  media:
    image: "/uploads/2019/11/29/Captura de ecrã de 2019-11-29 12-13-59.png"
    alt_text: Validator screenshot
- template: content-feature
  block: feature-1
  media_alignment: Right
  media:
    image: "/uploads/2019/11/29/editSiard.png"
    alt_text: Edit SIARD
  headline: "<strong>Edit SIARD metadata<br></strong>Enrich archived database with
    descriptions"
  content: Add descriptions to database, tables and columns to better understand its
    contents.
- template: content-feature
  block: feature-1
  media_alignment: Left
  headline: "<strong>Search records<br></strong>Browse and search database content"
  content: Google-like search on the database content.<br>Drill down on specific tables
    and do advanced search for specific fields to find exactly what you are looking
    for.
  media:
    image: "/uploads/2019/11/29/desktopSearchAll.png"
    alt_text: Search records
- template: content-feature
  block: feature-1
  media_alignment: Right
  headline: "<strong>Data load<br></strong>Import archived data into modern database
    system"
  content: Use the full query power of a modern database engine and enable advanced
    analytics like data mining.
  media:
    image: "/uploads/2019/11/29/desktopDataLoad.png"
    alt_text: Data Load
- template: hero-banner-w-image
  block: hero-2
  slug: enterprise
  headline: DBPTK Enterprise
  content: Web application to browse and search on the content of multiple large preserved
    databases.
  cta:
    enabled: true
    button_text: Read more
    url: https://github.com/keeps/db-visualization-toolkit-docker#database-preservation-toolkit-enterprise-deploy-as-docker
  background_image: ''
  image:
    image: "/icons/white/svg/012-cluster.svg"
    alt_text: Enterprise
- template: content-feature
  block: feature-1
  media_alignment: Right
  headline: "<strong>Enterprise Architecture<br></strong>For large institutions with
    many databases and users"
  content: A web application that can be horizontally scaled to support many very
    large databases being accessed by many users.
  media:
    image: "/uploads/2019/11/29/enterpriseArchitecture.png"
    alt_text: Enterprise architecture
- template: content-feature
  block: feature-1
  media_alignment: Left
  headline: "<strong>Manage multiple databases<br></strong>Single system, multiple
    databases"
  content: Search through the databases, manage their status, enrich their metadata,
    validate them, make them ready for users to search.
  media:
    image: "/uploads/2019/11/29/enterpriseManagement.png"
    alt_text: Enterprise management
- template: content-feature
  block: feature-1
  media_alignment: Right
  headline: "<strong>Advanced data transformation<br></strong>Transform content to
    answer useful questions"
  content: "<strong>De-normalization</strong> and table and <strong>column hiding</strong>,
    to simplify browsing/search and allow <strong>anonymization</strong> of content."
  media:
    image: "/uploads/2019/11/29/enterpriseTransformation.png"
    alt_text: Data transformation
- template: content-feature
  block: feature-1
  media_alignment: Left
  headline: "<strong>Single sign-on<br></strong>Support for multiple protocols"
  content: LDAP, Active Directory, Database, SAML, ADFS, OAuth2, OpenID, Google, Facebook,
    Twitter, FIDO U2F, YubiKey, Google Authenticator, Authy, etc.<br>Supports internal
    authorization definition or configurable external authorization.
  media:
    image: "/uploads/2019/11/29/enterpriseAuthentication.png"
    alt_text: Authentication
- template: content-feature
  block: feature-1
  media_alignment: Right
  headline: "<strong>Browse and search<br></strong>Allow users to access database
    content on the Web"
  content: Allow them to search on a prepared, de-normalized and anonymized database
    content.
  media:
    image: "/uploads/2019/11/29/enterpriseWebSearch.png"
    alt_text: Web search
- template: content-feature
  block: feature-1
  media_alignment: Left
  headline: "<strong>Export features<br></strong>Export data into tabular data"
  content: Allow users to save search results in Microsoft Excel or other spreadsheet
    software format for easy analytics and diagrams.
  media:
    image: "/uploads/2019/11/29/enterpriseExcel2.png"
    alt_text: Microsoft Excel
- template: hero-banner-w-image
  block: hero-2
  slug: developer
  headline: DBPTK Developer
  content: A command-line tool and development library for automation and system integration.
  cta:
    button_text: Read more
    url: https://github.com/keeps/db-preservation-toolkit#how-to-use
    enabled: true
  background_image: ''
  image:
    image: "/icons/white/svg/013-algorithm.svg"
    alt_text: Developer
- template: content-feature
  block: feature-1
  media_alignment: Right
  headline: "<strong>Command line interface<br></strong>Automation of periodic preservation
    tasks"
  content: Command line interface allows easy automation of periodic tasks like saving
    database to preservation format, validating, and editing metadata.
  media:
    image: "/uploads/2019/11/29/developerCLI.png"
    alt_text: Command-line interface
- template: content-feature
  block: feature-1
  media_alignment: Left
  headline: "<strong>Systems integration<br></strong>Java library"
  content: Library to allow integration of production systems to directly use database
    preservation features.
  media:
    image: "/uploads/2019/11/29/developerMaven.png"
    alt_text: Maven
- template: content-feature
  block: feature-1
  media_alignment: Right
  headline: "<strong>Open source<br></strong>For custom development"
  content: Code base that allows custom development of new features or specialized
    support for new or legacy database systems.
  media:
    image: "/uploads/2019/11/29/developerGithub.png"
    alt_text: GitHub
- template: simple-footer
  block: footer-1
  content: Made by <a href="https://www.keep.pt" title="KEEP Site">KEEP</a> with ❤︎

---
foo bar