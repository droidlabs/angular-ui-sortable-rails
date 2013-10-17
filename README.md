# Angular::Ui::Sortable::Rails

TODO: Write a gem description

## Installation

Add gem to your Gemfile & run `bundle install` in the terminal:

    gem 'angular-ui-sortable-rails'

## Usage

```
app = angular.module 'app', ['ui.sortable.rails']
```

```
div (ng-model='data.blocks' ui-sortable="{update: updateSrting, containment: 'parent', axis: 'y', cursor: 'move'}")
  div.common-box (ng-repeat="block in data.blocks" dynamic-directive)
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
