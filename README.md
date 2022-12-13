# JS Pimcore FormBuilder Extensions

We're providing some helpful Javascript Extensions to simplify your daily work with the PIMCORE FormBuilder.
This Library provides all JS components for the [PIMCORE FormBuilder Bundle](https://github.com/dachcom-digital/pimcore-formbuilder).

## Installation
```bash
npm i js-pimcore-formbuilder
```

## Extensions Overview
- [Fetch Manager](./docs/01_fetch_manager.md)
- [Conditional Logic Component](./docs/02_conditionalLogic.md)
- [Repeater Component](./docs/03_repeater.md)
- [Tracker Component](./docs/04_tracker.md)
- [reCAPTCHA V3 Component](./docs/05_recaptchaV3.md)
- [Dynamic Multi File Libraries](./docs/06_dynamic_multi_file.md)
    - [Drop Zone](./10_dmf_drop_zone.md)

## Upgrade Notes

### 1.0.6
- **[BUGFIX]**: Do not submit general error event multiple times
- **[BUGFIX]**: Do not dispatch delete file event, after form gets cleared out

### 1.0.5
- **[BUGFIX]**: ReCaptcha token assignment not working [@patric-eberle](https://github.com/dachcom-digital/js-pimcore-formbuilder/issues/5)
- **[BUGFIX]**: ReCaptcha Hash never updated  [@patric-eberle](https://github.com/dachcom-digital/js-pimcore-formbuilder/issues/9)
- **[BUGFIX]**: Options are shared between instances [@patric-eberle](https://github.com/dachcom-digital/js-pimcore-formbuilder/issues/8)

### 1.0.4
- **[BUGFIX]**: Fix removeAttributes in transformers

### 1.0.3
- **[BUGFIX]**: Fix enable/disable actions in conditional logic

### 1.0.2
- **[ENHANCEMENT]**: Improve Tailwind2 validation message
- **[ENHANCEMENT]**: Update docs

### 1.0.1
- **[ENHANCEMENT]**: Update readme
- **[ENHANCEMENT]**: Update docs

### 1.0.0
- New Theme Transformer available: Tailwind 2
