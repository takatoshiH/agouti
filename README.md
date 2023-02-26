# Agoutiのディレクトリ構造

```
.
├── CONTRIBUTING.md
├── LICENSE
├── README.md
├── THANKS.md
├── agouti.go
├── agouti_suite_test.go
├── api
│   ├── api.go
│   ├── api_suite_test.go
│   ├── element.go
│   ├── element_test.go
│   ├── injector_test.go
│   ├── internal
│   │   ├── bus
│   │   │   ├── bus_suite_test.go
│   │   │   ├── client.go
│   │   │   ├── client_test.go
│   │   │   ├── connect.go
│   │   │   └── connect_test.go
│   │   ├── mocks
│   │   │   ├── bus.go
│   │   │   └── service.go
│   │   └── service
│   │       ├── build.go
│   │       ├── service.go
│   │       ├── service_suite_test.go
│   │       └── service_test.go
│   ├── mobile
│   │   ├── mobile_suite_test.go
│   │   ├── session.go
│   │   └── session_test.go
│   ├── offset.go
│   ├── session.go
│   ├── session_test.go
│   ├── speed.go
│   ├── types.go
│   ├── webdriver.go
│   ├── webdriver_test.go
│   ├── window.go
│   └── window_test.go
├── appium
│   ├── appium_suite_test.go
│   ├── device.go
│   ├── injector_test.go
│   ├── mock_session_test.go
│   ├── options.go
│   ├── selection.go
│   ├── touchaction.go
│   ├── touchaction_test.go
│   └── webdriver.go
├── capabilities.go
├── capabilities_test.go
├── go.mod
├── injector_test.go
├── internal
│   ├── element
│   │   ├── element_suite_test.go
│   │   ├── repository.go
│   │   └── repository_test.go
│   ├── integration
│   │   ├── integration.go
│   │   ├── integration_suite_test.go
│   │   ├── integration_test.go
│   │   ├── mobile_test.go
│   │   ├── mobile_test_page.html
│   │   ├── page_test.go
│   │   ├── selection_test.go
│   │   └── test_page.html
│   ├── matchers
│   │   ├── exactly_equal.go
│   │   ├── exactly_equal_test.go
│   │   └── matchers_suite_test.go
│   ├── mocks
│   │   ├── bus.go
│   │   ├── element.go
│   │   ├── element_repository.go
│   │   ├── session.go
│   │   └── webdriver.go
│   └── target
│       ├── selector.go
│       ├── selector_test.go
│       ├── selectors.go
│       ├── selectors_test.go
│       └── target_suite_test.go
├── matchers
│   ├── internal
│   │   ├── be_found.go
│   │   ├── be_found_test.go
│   │   ├── boolean_matcher.go
│   │   ├── boolean_matcher_test.go
│   │   ├── colorparser
│   │   │   ├── color_parser.go
│   │   │   ├── colorparser_suite_test.go
│   │   │   └── colorparser_test.go
│   │   ├── equal_element.go
│   │   ├── equal_element_test.go
│   │   ├── have_attribute.go
│   │   ├── have_attribute_test.go
│   │   ├── have_css.go
│   │   ├── have_css_test.go
│   │   ├── internal_suite_test.go
│   │   ├── log_matcher.go
│   │   ├── log_matcher_test.go
│   │   ├── match_text.go
│   │   ├── match_text_test.go
│   │   ├── messages.go
│   │   ├── mocks
│   │   │   ├── page.go
│   │   │   └── selection.go
│   │   ├── value_matcher.go
│   │   └── value_matcher_test.go
│   ├── matchers.go
│   ├── matchers_suite_test.go
│   ├── page_matchers.go
│   ├── page_matchers_test.go
│   ├── selection_matchers.go
│   └── selection_matchers_test.go
├── multiselection.go
├── multiselection_test.go
├── options.go
├── options_test.go
├── page.go
├── page_test.go
├── selectable.go
├── selectable_test.go
├── selection.go
├── selection_actions.go
├── selection_actions_test.go
├── selection_frames.go
├── selection_frames_test.go
├── selection_properties.go
├── selection_properties_test.go
├── selection_test.go
├── types.go
└── webdriver.go
```