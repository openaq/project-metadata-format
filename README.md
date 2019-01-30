
# project-metadata-format
This repo houses project discussions for building a metadata format for the metadata editor.

## 1. Background on the Problem This Project Addresses

[OpenAQ](https://openaq.org) aggregates air quality data from disparate governmental and research sources across the world and harmonizes them into one consistent [data format](https://github.com/openaq/openaq-data-format). The metadata that is readily and commonly available across all of the disparate data sources are limited to a few parameters (See [OpenAQ's data format](https://github.com/openaq/openaq-data-format) to view the minimum data and metadata requirements for the platform, which are also consistent with the most commonly readily available metadata provided by sources). 

Consequently, OpenAQ currently has no practical way of gathering and sharing information on additional valuable metadata, such as instrument types, calibration procedures, or other relevant information about measurements taken at a given station location. Additionally, there is no current consistent way in the platform in which various features such as "station environment" (e.g. the area immediately surrounding an air quality monitoring station) are characterized across disparate source sites. Lastly, even at source locations where abundant metadata are provided at the source, it is often the case that either the data are not readily available in a programmatic (i.e. computer-readable) format or, b) in identical, harmonized formats with other data sources.

Feedback from the OpenAQ Community has made clear that for many impactful uses of these open air quality data, it is often useful or even necessary to have additional metadata and systems of classifying various station-level features. 

Fortunately, many data providers are willing to share metadata, while other forms of metadata can potentially even be contributed by observations from the general public (e.g. information about the immediate surroundings of an air quality monitoring station). 

The gap currently is having a systematic, harmonized way to both collect and programmatically share these metadata. This project seeks to address this gap.


## 2. Project Purpose and Description

To address the problem outlined above, OpenAQ, along with our partners and the broader OpenAQ Community, are building a metadata editor and formulating an initial stab at a metadata format to share. The metadata editor will be a tool that will allow individuals to input metadata information for air quality stations, which will create a database of uniformally-formatted metadata for air quality stations across the world. It will also allow a user to programmatically access the information via an open (and free) Application Programming Interface. 

All code and data associated with the platform will reside in an open-source repo on the [OpenAQ Project on GitHub](https://github.com/openaq) under the same highly permissible licenses as the rest of the OpenAQ platform (more information available [here for the open data](https://github.com/openaq/openaq-info/blob/master/FAQ.md#license) and [here for the open-source code](https://github.com/openaq/openaq-info/blob/master/FAQ.md#licenseopensource)).

Another piece of this project is building a universal station ID system. Please see [this related GitHub repo](https://github.com/openaq/project-universal-stationID) for more information.


## 3. Call for Community Input on Parameters to Include in Metadata Format

We are seeking input on what types of metadata the community will find most useful to include in this data format - and ultimately what we will seek to make accessible from data source providers via the metadata editor. While not all metadata proposed to be included in this initial format will necessarily be able to be included for a variety of reasons, from general availability of the information to logistical constraints, it will still be informative both for the short term of this project and in the longer term for others' benefits to get input from as broad a swath of the OpenAQ Community as possible.

### **If you are interested in contributing comments on what types of metadata you would find most useful to be included in this data format, please make an "Issue" in this repo. You can read more [here](https://github.com/openaq/project-metadata-format/issues/2#issue-404989177) on how to do this.** 

This will require that you have a GitHub Account. If you prefer not to use GitHub, please send your input to info@openaq.org, and we will make an issue on your behalf, including your name and affiliation, as available and unless otherwise instructed to not do so. If you are interested in providing input on another piece of this project on building a universal station ID system, please see [this related GitHub repo](https://github.com/openaq/project-universal-stationID) for more information.


## 4. Sponsors and Partners in this Work

This work is sponsored by the IntelliAQ Team at [Forschungszentrum Jülich GmbH](http://www.fz-juelich.de/portal/DE/Home/home_node.html) through a grant from the European Research Council: ERC-2017-ADG #787576. [Development Seed](https://developmentseed.org/) is constructing the metadata editor. As always, the larger OpenAQ Community is also providing key input to shape the project in the ways that best support their diverse and impactful air inequality works.

For reference, other sponsors of OpenAQ are listed [here](https://openaq.org/#/about).


