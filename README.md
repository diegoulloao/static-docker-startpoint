# Static HTML Server in Docker

- **Repository:**
	- A docker enviroment for serve static html files with nginx.
- **Stack:** CSS, JS, HTML5.
- **Services:** Nginx.
- **Year:** 2020.

This repository provides a nginx server for static html files.

## Step 1. Clone the repository.

Browse your projects location and run:

```bash
git clone git@github.com:diegoulloao/static-docker-startpoint.git project-name
```

## Step 2. Create static html files.

Enter in the`project-name` directory and browse `html` folder, create your html files.

## Step 3. Run the service.

Run:

```
docker-compose up
```

Open up your browser to http://localhost:8080/ and you should see your page as intended. **Only .html extension files will be interpreted.**

--

**@diegoulloao · 2020**