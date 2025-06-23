# EDW Person

Enable the person module to provide content managers with the ability to manage people within Drupal.

## Installation

1. Add the following snippet to the `repositories` section of your `composer.json` file:
```
{
    "type": "git",
    "url": "https://github.com/eaudeweb/edw_person.git"
}
```

2. Run
   ```composer require eaudeweb/edw_person:^1.0```

3. Enable the module:
   ``drush en edw_person``

### Fields

| Field label | Field name      | Description                                | Field type       | Cardinality | Required | Translatable | Widget     |
|-------------|-----------------|--------------------------------------------|------------------|-------------|----------|--------------|------------|
| Title       | title           |                                            | Text             | Single      | Yes      | Yes          | Text field |
| Body        | body            |                                            | -                | -           | -        | -            | -          |
| Countries   | field_countries | Taxonomy term entity reference (Countries) | Entity reference | Single      | No       | No           | Select     |
| Website     | field_website   |                                            | Link             | Single      | No       | No           | TODO       |
| Email       | field_email     |                                            | Email            | Single      | No       | No           | TODO       |

### Taxonomies

None

### Paragraphs
Use the [edw_paragraphs](https://github.com/eaudeweb/edw_paragraphs) module to enable different visual components that can be added to the meeting sections. 
Use [countries_import](https://www.drupal.org/project/countries_import) module to import Geographical coverage.

## Other EDW modules:
* [edw_decoupled](https://github.com/eaudeweb/edw_decoupled)
* [edw_demo_data](https://github.com/eaudeweb/edw_demo_data)
* [edw_document](https://github.com/eaudeweb/edw_document)
* [edw_event](https://github.com/eaudeweb/edw_event)
* [edw_group](https://github.com/eaudeweb/edw_group)
* [edw_media](https://github.com/eaudeweb/edw_media)
* [edw_paragraphs](https://github.com/eaudeweb/edw_paragraphs)
* [edw_person](https://github.com/eaudeweb/edw_person)
* [edw_project](https://github.com/eaudeweb/edw_project)
* [edw_themes](https://github.com/eaudeweb/edw_themes)
* [edw_utilities](https://github.com/eaudeweb/edw_utilities)