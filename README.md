# README

This project has been donated to Apache Arrow: https://github.com/apache/arrow/tree/master/ruby/red-arrow-gpu

## Name

Red Arrow GPU

## Description

Red Arrow GPU is a Ruby bindings of Apache Arrow GPU. Red Arrow GPU is based on GObject Introspection.

[Apache Arrow GPU](https://arrow.apache.org/) is an in-memory columnar data store on GPU.

[GObject Introspection](https://wiki.gnome.org/action/show/Projects/GObjectIntrospection) is a middleware for language bindings of C library. GObject Introspection can generate language bindings automatically at runtime.

Red Arrow GPU uses [Apache Arrow GPU GLib](https://github.com/apache/arrow/tree/master/c_glib) and [gobject-introspection gem](https://rubygems.org/gems/gobject-introspection) to generate Ruby bindings of Apache Arrow GPU.

Apache Arrow GPU GLib is a C wrapper for [Apache Arrow GPU C++](https://github.com/apache/arrow/tree/master/cpp). GObject Introspection can't use Apache Arrow GPU C++ directly. Apache Arrow GPU GLib is a bridge between Apache Arrow GPU C++ and GObject Introspection.

gobject-introspection gem is a Ruby bindings of GObject Introspection. Red Arrow GPU uses GObject Introspection via gobject-introspection gem.

## Install

Install Apache Arrow GPU GLib before install Red Arrow GPU. Use [packages.red-data-tools.org](https://github.com/red-data-tools/packages.red-data-tools.org) for installing Apache Arrow GPU GLib.

Install Red Arrow GPU after you install Apache Arrow GPU GLib:

```text
% gem install red-arrow-gpu
```

## Usage

```ruby
require "arrow-gpu"

# TODO
```

## Dependencies

* [Apache Arrow](https://arrow.apache.org/)

* [Arrow GLib](https://github.com/apache/arrow/tree/master/c_glib)

* [gobject-introspection gem](https://rubygems.org/gems/gobject-introspection)

## Authors

* Kouhei Sutou \<kou@clear-code.com\>

## License

Apache License 2.0. See `doc/text/apache-2.0.txt` and `NOTICE` for
details.

(Kouhei Sutou has a right to change the license including contributed
patches.)
