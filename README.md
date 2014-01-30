This is free software licensed under the [GNU GENERAL PUBLIC LICENSE
V3](http://www.gnu.org/licenses/gpl.html)

    San Francisco Record: Layout Module Example for Newstime Platform
    Copyright (C) 2014  Blake S. Taylor

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

The San Francisco Record Name and Logotype are trademarked and copyrighted works
owned by Blake Sebastian Taylor and may not be used without express
written permission. Copyright 2014, All Rights Reserved.

This is the beginning of an experimental system for rendering and organizing
templates that will be used for rendering news editions.

### Main Section

templates/main, by convention is the main template and will be used as the first
template rendered.

This template should yield when the content will go.

### _page.html.erb

This is the default page partial. If include, it will wrap each page and can be
used to include page numbers and the like.

## Project Breakdown

The layout project contains view, stylesheets, javascripts, images and fonts.


### Views

# Views go under `/views`. The recommended templating language to use is erb, but you can use any supported templating system.

### Javascripts

Javascripts go under `/javascrips`. These will be available from /javascript from the root of the edition
