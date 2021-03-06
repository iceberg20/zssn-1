# Change Log

## [1.2.0] - 2017/06/18

### Added

* GET `/survivors` to retrieve all registered survivors.

### Changed

* GET `/items` json response removed the data and message field.

## [1.1.0] - 2017/06/12

### Added

* GET `/items` to retrieve all registered items.

## [1.0.2] - 2017/06/12

### Added

* [rack-cors](https://github.com/cyu/rack-cors) to enable cross origin AJAX.

## [1.0.1] - 2017/04/27

### Changed

* On `/survivor/{id}/report` when reporting the same survivor now returns an error message.

## [1.0.0] - 2017/04/27

### Added
* POST `/survivors/{id}/trade` to trade items between survivors
* GET `/reports/infected` to get the infected percentage.
* GET `/reports/non_infected` to get the healthy percentage.
* GET `/reports/average_resource` to get the average amount of each kind of resource.
* GET `/reports/points_lost` to get the amount of points lost because of the infected.
* POST `/survivors/{id}/report` to report a infected survivor.
* PUT `/survivors/{id}` endpoint to update a Survivor`s location.
* POST `/survivors` endpoint to register a Survivor.
* Inventory model that represents a survivor inventory.
* Survivor model that represents a infected or non-infected person.
* Stack model that represents a stack of items.
* Item model that represents an item.
* Use [ActiveModel::Serializer](https://github.com/rails-api/active_model_serializers) for model serialization into JSON.
* Use [Factory Girl](https://github.com/thoughtbot/factory_girl_rails) as a fixture replacement.
* Use [RSpec](http://rspec.info/) for unit testing.
* Init project using [Rails 5.0](http://guides.rubyonrails.org/5_0_release_notes.html).

[1.2.0]: https://github.com/JayBIOS/zssn/releases/tag/v1.2.0
[1.1.0]: https://github.com/JayBIOS/zssn/releases/tag/v1.1.0
[1.0.2]: https://github.com/JayBIOS/zssn/releases/tag/v1.0.2
[1.0.1]: https://github.com/JayBIOS/zssn/releases/tag/v1.0.1
[1.0.0]: https://github.com/JayBIOS/zssn/releases/tag/v1.0.0
