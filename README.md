# Emergency Relief Package Tracker

> Managing and tracking emergency relief packages across cities, regions, and countries.

![Emergency Relief Tracking Screenshot](/screenshot.jpg)

## About

This project is designed to help local organizations and government institutions help track distribution of emergency relief packages along with their contents to ensure essential supplies are evenly distributed.

## Getting Started


1. Create a Postgres database and add the PostGIS extension.

2. Make sure you have [NodeJS](https://nodejs.org/) and [npm](https://www.npmjs.com/) installed.
3. Create a `.env` file to include the details for your Postgres instance and database and include the following:

    ```
    PGNAME= <db username>
    PGPASS= <db password>
    PGDB= <db name>
    PGPORT=5432
    ```
4. Install your dependencies

    ```
    cd path/to/emergency-relief-tracker
    npm install
    ```

5. Start your app

    ```
    npm start
    ```

## Testing

Simply run `npm test` and all your tests in the `test/` directory will be run.
