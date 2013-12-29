# REST Guide

apitrary uses RESTful APIs as backend for your applications. This guide will give you an detailled introduction to the API endpoints you will need to contact in order to store and retrieve information.

## Base URL

apitrary will generate backends for your applications in very easy steps. A backend consists of a generated REST API with a set of REST endpoints. All endpoints will use following base URL:

[https://_YOUR_API_ID_.api.apitrary.com/](https://api.apitrary.com/ "API endpoint URL")

## Endpoints

Following will give you a brief overview of the provided endpoints:

<table>
	<tr>
		<th>Endpoint</th>
		<th>Verbs</th>
		<th>Comment</th>
	</tr>
	<tr>
		<td><a href="#get_single_object" alt="Single Object GET">/:entity_name/:object_id</a></td>
		<td>GET</td>
		<td>Retrieve single object</td>
	</tr>
	<tr>
		<td><a href="#post_single_object" alt="Single Object POST">/:entity_name</a></td>
		<td>POST</td>
		<td>Store a single object</td>
	</tr>
	<tr>
		<td><a href="#update_single_object" alt="Single Object PUT">/:entity_name/:object_id</a></td>
		<td>PUT</td>
		<td>Update single object</td>
	</tr>
	<tr>
		<td><a href="#delete_single_object" alt="Single Object DELETE">/:entity_name/:object_id</a></td>
		<td>DELETE</td>
		<td>Delete single object</td>
	</tr>
	<tr>
		<td><a href="#get_single_object" alt="Single Object GET">/:entity_name/:object_id</a></td>
		<td>GET</td>
		<td>Retrieve single object</td>
	</tr>
	<tr>
		<td><a href="#search_for_objects" alt="Search objects">/:entity_name?q=:search_expression</a></td>
		<td>GET</td>
		<td>Search for objects</td>
	</tr>
</table>


## HTTP Verbs

apitrary is using 

### GET: Retrieving a single object

Talk about how to retrieve single objects from our data store.

Show JSON example with curl

### POST: Storing a single object

Talk about how to store an object.

Show JSON example with curl

### PUT: Updating an existing object

Talk about how to store an object.

Show JSON example with curl

### DELETE: Delete an existing object

Talk about how to store an object.

Show JSON example with curl

Talk about the READ-/WRITE-Quorum of Riak and that developers might need to wait a bit before re-retrieving data from the data store.

## Search

Show a simple example on how to search for a field and a given value in this field. Tell the user to look into our extensive search guide (also only examples from Riak Solr).

Also tell the developer/reader to look into Solr search.