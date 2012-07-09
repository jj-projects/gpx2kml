# trk2rte

## Description

 This java application takes an XMLTrackFile (GPX Format) and converts it into an KML file.

## Ant Build

On project level execute:
	ant -buildfile build/build.xml run
	

## Usage

java -classpath gpx2kml.jar de.jjprojects.gpx2kml.gpx2kml -Djava.util.logging.config.file=gpx2kml_logging.properties <XmlTrackFile>  <KmlFile>


## Author

Joerg Juenger ( jj-projects, joerg@jj-projects.de ), JJ-Projects Joerg Juenger

## Licenses

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.
