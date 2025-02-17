# Changelog

## [Unreleased]

## 17.2.41 (2019-08-14)

### TreeGrid

#### Bug Fixes

- `#243065` - `expandAll` and `collapseAll` method works fine for remote data with `loadChildOnDemand` property as true.

## 17.2.40 (2019-08-06)

### TreeGrid

#### Bug Fixes

- `#146272` - Ellipsis works fine for tree-view column.

- `#146212` - Template works fine for dynamic columns.

## 17.2.39 (2019-07-30)

### TreeGrid

#### Bug Fixes

- #145979 - `checkboxChange` event will trigger for header cell check.
- #240702 - `allowEditOnDblClick` works fine in Cell Edit mode.

#### Breaking Changes

- `checkboxChange` event will trigger after the cell checked.

## 17.2.35 (2019-07-17)

### TreeGrid

#### Bug Fixes

- `crudaction` works fine while performing crud actions with server-side.

## 17.2.28-beta (2019-06-27)

### TreeGrid

#### New Features

- Virtual Scrolling support has been provided in which the rows are added dynamically while scrolling.
- Detail Template support has been provided that provides additional information about a particular row.

#### Bug Fixes

- `collapseAll` method works fine with pageSize mode set to `All`.

#### Breaking Changes

- The default value of `enableHover` property has been changed from `true` to `false`.

## 17.1.1-beta (2019-01-29)

### TreeGrid

#### Bug Fixes

- `Query` maintenance support provided for `refresh` method after expanding any child rows.
- Property change support for `height` property has been provided.
- Expand icon is prevented from displaying for the root/zeroth level record which has `hasChildMapping` field as false.
- Child records of third level or its successor displays properly based on their hierarchy relation in self reference data binding.

- Expand icon is prevented from displaying for the root/zeroth level record which has `hasChildMapping` field as false.

#### New Features

- `Excel-Like Filtering` support is provided that allows users to create complex filter criteria for a column by allowing users to select possible filter values from a checkbox list. The advanced filter can be used to build complex filter criteria.

## 16.4.45 (2019-01-02)

### TreeGrid

#### Bug Fixes

- Added events for the column menu feature and added `columnMenuItems` API to modify the column menu items in column menu.
- Added `sortComparer` API to perform custom sorting in TreeGrid.

## 16.4.44 (2018-12-24)

### TreeGrid

#### Bug Fixes

- Expanding and Collapsing records is working fine when `pageSizeMode` is set as `All`.
- `expandAtLevel`, `collapseAtLevel`, `expandAll` and `collapseAll` methods are working fine when `pageSizeMode` is set as `All`.


- `actionBegin`, `actionComplete` and `actionFailure` events are triggered properly.
- Additional parameters that are added using the `query` property of TreeGrid are passed to the server side when a parent record is expanded.


