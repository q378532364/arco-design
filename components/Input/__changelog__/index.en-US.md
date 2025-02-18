## 2.23.0

2021-09-27

### 🆕 Feature

- The `Input` component `maxLength` supports the `errorOnly` mode. When exceeding `maxLength`, user input will not be restricted, but error status will be displayed

## 2.18.0

2021-07-02

### ⚠️ Important attention

- `Input.Group`: Group -> InputGroup
- `Form.Item`: Item -> FormItem
- `Menu.Item`: Item -> MenuItem
- `Timeline.Item`: Item -> TimelineItem
- `Tree.Node`: Node -> TreeNode
- When you set both `allowClear` and `props.className`, the className will be incorrectly applied to the inner input tag. **Sorry this change may cause breaking changes, please pay attention**.



## 2.17.3

2021-06-24

### 🐛 Bugfix

- Fix the issue that `Input.Search` does not trigger `onPressEnter`.

## 2.16.0

2021-05-28

### 🐛 Bugfix

- Fix the problem that the `Input` style fails to compile in less 4.x.

## 2.15.3

2021-05-21

### 🐛 Bugfix

- Fix the bug that the `Input` tag rendered in the `footer` of the `Cascader` component cannot be focused.



## 2.15.2

2021-05-14

### 🐛 Bugfix

- Fix the bug that the search button on the right is not disabled when `Input.Search` is disabled.

## 2.13.2

2021-04-01

### 💅 Style

- Adjust the left and right padding styles of `Input` components of different sizes.
- Fix the problem that the height of the input box becomes 100% of the height of the parent element when the height of the parent element is set for the `Input` component and `allowClear` is set.



## 2.13.0

2021-03-26

### 🐛 Bugfix

- Fix the bug that the content in the input box cannot be selected by the mouse when the `Input` component uses `addBefore`.

## 2.9.1

2021-02-20

### 🐛 Bugfix

- When the `Input.Search` component is disabled, clicking the search icon still triggers the `onSearch` callback bug.



## 2.8.2

2021-01-29

### 💅 Style

- Fix the disabled style of `Input` not working in Safari.

## 2.8.1

2021-01-28

### 🐛 Bugfix

- Fixed the bug that the `Input` component introduced full icons, which caused the on-demand loading to fail.



## 2.8.0

2021-01-22

### 💅 Style

- Fix the issue that the split line style of the prefix and suffix of the `Input` component is lost.

