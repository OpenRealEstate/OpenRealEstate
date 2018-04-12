

# OpenRealEstate.NET

This is the home page / project overview for the OpenRealEstate project and is intended for kind folks who are learning to integrate this system into their own system(s) or to contribute to the project.

OpenRealEstate is a project that models realestate listings for any country. It's based off a common schema, which is then represented by various code languages, packaged up into easy-to-use libraries.

The ethos of this project is to have a common, open and uniform way to represent what a property listing is.

---

### Repository hierachy
The repositories are organised into a hierachy, following some Namespace and Area conventions:

| Project        | Language                 | Area                       |
| ---------------|--------------------------|----------------------------|
| OpenRealEstate | <.NET / Go / Ruby / etc> | <Core / Validation / etc.> |

| Area             | Description |
|------------------|-------------|
| Core             | Domain models that represent the common schema. |
| Transmorgrifiers | Parsers for converting other proprietory formats into an OpenRealEstate domain model. |
| Validation       | Validation rules. |
| FakeData         | (Optional) A nice helper library to quickly generate fake data. |

e.g.
- `OpenRealEstate.NET.Core`
- `OpenRealEstate.NET.Transmogrifier.RealestateComAu`
- `OpenRealEstate.NET.Transmogrifier.Csv`

... etc.

> FUN FACT: What is a `Transmogrifier`? To [quote Wiki](http://calvinandhobbes.wikia.com/wiki/Transmogrifier): "The Transmogrifier is an invention of Calvin's that would turn one thing into another."

## Contributing

Discussions and pull requests are encouraged :) Please ask all general questions in this repo or pick a specialized repo for specific, targeted issues. We also have a [contributing document](https://github.com/OpenRealEstate/OpenRealEstate/blob/master/CONTRIBUTING.md) which goes into detail about how to do this.

## Code of Conduct
Yep, we also have a [code of conduct](https://github.com/OpenRealEstate/OpenRealEstate/blob/master/CODE_OF_CONDUCT.md) which applies to all repositories in the OpenRealEstate organisation.

## Languages supported
- .NET under .NET Standard. Packages available on NuGet.

## Feedback
Check out the contributing page to see the best places to log issues and start discussions.

---
