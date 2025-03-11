# Emergency Department Dashboards

This project is a public demonstration of one way software engineering teams can create emergency department dashboards. 

We welcome constructive feedback via GitHub issues or email joel.henderson@wales.nhs.uk.

About this project:

* The software engineering uses SvelteKit, which is a popular free open source JavaScript/TypeScript web application framework, originally developed by the New York Times to visualize data.

* The data engineering uses all fabricated information, that does not include any data from any real persons.

The purpose of this project is to help demonstrate software engineering practices:

* Front-end UI. This project uses Svelte.

* Front-end UI components. This project uses Storybook.

* Unit testing. This project uses Vitest.

* End-to-end testing. This project uses Playwright and Chromium.

* Type checking. This project uses Typescript.

* Code formatting. This project uses Prettier.

* Code linting. This project uses ESLint.

* Utility-first CSS. This project uses Tailwind.

* Database connectivity. This project uses Drizzle with PostgreSQL.

* Authentication. THis project uses Lucia.

* Internationalization. This project uses Paraglide.

* Markdown preprocessing. This project uses msdvex.

* Package management. This project uses pnpm.


## How to run this project

This project uses these programs and versions:

* git 2.48.1
* node 23.6.1
* npx 11.1.0
* pnpm 10.5.2

To verify you have these programs and similar versions:

```sh
git --version
node --version
npx --version
pnpm --version
```

Get the project source code:

```sh
git clone https://github.com/GIG-Cymru-NHS-Wales/emergency-department-dashboards.git
```

Change directory:

```sh
cd emergency-department-dashboards 
```

Run the project in your web browser:

```sh
pnpm run dev --open
```

## How to create this project from scratch

Install `node` and `npx` as you wish.

Create the project by choosing your favorite way such as:

```sh
npx sv@latest create emergency-department-dashboards --template minimal --types ts
```

Change directory:

```sh
cd emergency-department-dashboards 
```

Create the version control by choosing your favorite way such as:

```sh
git init && git add -A && git commit -m "Start"
```

Run the project in your web browser:

```sh
pnpm run dev --open
```

Add language support:

```sh
git add project.inlang && git commit -m "Add language support"
```

## Add-on next steps
                                                                   
drizzle:                                                            

- You will need to set DATABASE_URL in your production environment 

- Run pnpm run db:start to start the docker container               

- Run pnpm run db:push to update your database schema               

lucia:                                                              

- Run pnpm run db:push to update your database schema              

- Visit /demo/lucia route to view the demo  
                                                                      
paraglide:                                                          

- Edit your messages in messages/en.json                            

- Consider installing the Sherlock IDE Extension                    

- Visit /demo/paraglide route to view the demo                      
