<h1>GTFS Collection<h1/>
                <p>Please create an issue and include the URL to the GTFS data if you would like to add a new city. The format should be the following: <br>```city=berlin_germany,url=https://developers.google.com/transit/gtfs/examples/sample-feed.zip```<p/>
            <h1>Current Status<h1/>
            <table>
                <tr>
                    <th>City</th>
                    <th>Import date</th>
                    <th>Expire date</th>
                    <th>Source URL</th>
                </tr>
                <tr>
                    <td>
                        <a href='https://github.com/gtfs-collection/' + properties['city'] + '>' + properties['city'] + </a>(
                        <a href='https://github.com/gtfs-collection/' + properties['city'] + '/archive/master.zip'>ZIP</a>
                        <a href='https://github.com/gtfs-collection/overview/blob/master/polygons/' + properties['city'] + '.geojson'>Polygon</a>)
                        </td>
                    <td>' + properties['import_date'] + '</td>
                    <td>' + properties['expire_date'] + '</td>
                    <td>' + properties['url'] + '</td>
                <tr/>
                <tr>
                    <td>
                        <a href='https://github.com/gtfs-collection/' + properties['city'] + '>' + properties['city'] + </a>(
                        <a href='https://github.com/gtfs-collection/' + properties['city'] + '/archive/master.zip'>ZIP</a>
                        <a href='https://github.com/gtfs-collection/overview/blob/master/polygons/' + properties['city'] + '.geojson'>Polygon</a>)
                        </td>
                    <td>' + properties['import_date'] + '</td>
                    <td>' + properties['expire_date'] + '</td>
                    <td>' + properties['url'] + '</td>
                <tr/>
                <tr>
                    <td>
                        <a href='https://github.com/gtfs-collection/' + properties['city'] + '>' + properties['city'] + </a>(
                        <a href='https://github.com/gtfs-collection/' + properties['city'] + '/archive/master.zip'>ZIP</a>
                        <a href='https://github.com/gtfs-collection/overview/blob/master/polygons/' + properties['city'] + '.geojson'>Polygon</a>)
                        </td>
                    <td>' + properties['import_date'] + '</td>
                    <td>' + properties['expire_date'] + '</td>
                    <td>' + properties['url'] + '</td>
                <tr/></table>