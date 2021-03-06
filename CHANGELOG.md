# CHANGELOG

## 3.1.0 - 2016-11-29

- Add CHANGELOG.
- Use Chart.js v2.4.0

**WARNING**: Breaking changes: #3356 The default aspect ratio is now correctly
applied, meaning that polar, doughnut and radar charts are now rendered with an
aspect ratio of 1 (square). The old behavior can be obtained by globally changing
the default aspectRatio for each chart type (e.g.
Chart.defaults.doughnut.aspectRatio = 2).


## 3.0.2 - 2016-06-13

- Add pie chart helper.


## 3.0.1 - 2016-06-10

- Add horizontal bar chart helper.


## 3.0.0 - 2016-06-08

- Use Chart.js v2.1.4 (backwards incompatible).


## 2.2.0 - 2015-08-26

- Use Chart.js v1.0.2.


## 2.1.3 - 2015-08-26

- AJAX and Turbolinks compatibility.


## 2.1.2 - 2015-08-18

- Pass `onAnimationComplete` and `onAnimationProgress` functions correctly.


## 2.1.1 - 2015-03-13

- Provide original helpers with easy way to opt out.
- Namespace the view helpers.
- Fix name of polar_area_chart in README.
- Ensure any old charts are cleaned up.
- Clarify optional features.
- State Chart.js version in README.


## 2.1.0 - 2015-01-14

- Use Chart.js v1.0.1.
- Support Turbolinks.
- Do not generate a legend by default.


## 2.0.0 - 2014-11-07

- Use Chart.js 1cfa42bc (a little after v1.0.1-beta.4).
- Wrap generated JavaScript snippet in a closure.
- Use Chart.js' legends.
- Update README.
- Add link to scale calculation issue.


## 1.1.1 - 2014-03-20

- Rails 4 compatibility.


## 1.1.0 - 2014-03-14

- Use Rails' asset pipeline.


## 1.0.1 - 2013-06-21

- Opt-in alternative scale calculations.
- Code for filling gaps in series.


## 1.0.0 - 2013-06-16

- First release.
