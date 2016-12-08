# Rumbl

A video annotation application written in Elixir/Phoenix. This code is based on the first 11 chapters of the Programming Phoenix book, v.P1.0 --April 2016.

NOTE: You must rename the config/dev.secret.dist to config/dev.secret and edit the line:

config :rumbl, :wolfram, app_id: "XXXXXX-XXXXXXXXXX"

to add your own Wolfram-Alpha id for the InfoSys component of this app to run properly.

To start your Phoenix app:

  * Install dependencies with `mix deps.get`
  * Create and migrate your database with `mix ecto.create && mix ecto.migrate`
  * Install Node.js dependencies with `npm install`
  * Start Phoenix endpoint with `mix phoenix.server`

Now you can visit [`localhost:4000`](http://localhost:4000) from your browser.

