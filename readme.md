# The OpenUI Design System

A global, accessible, and themeable design system for the web platform.

## What is OpenUI Design System?

The OpenUI Design System is a collaborative effort to create a standardized set of UI components that can be used across the web. It aims to:

- Provide high-quality, accessible components that work across any web framework
- Reduce duplicative effort in rebuilding common UI patterns
- Improve the overall quality and accessibility of web experiences
- Create a bridge between low-level HTML elements and organization-specific design systems and individual web products
- Serve as an incubator for potential future HTML elements and attributes

The OpenUI Design System provides Web Components that are:

- Framework-agnostic
- Highly accessible by default
- Completely themeable
- Internationalized
- Composable and extensible
- Built on web standards
- Meet a high bar of quality based on [thorough criteria](https://docs.google.com/document/d/1eTSxCWd3yRMxTCAs3a74NzQ6C9gikYQLZeVdCMODwOg/edit?tab=t.0#heading=h.jjvcvbvmo8v1)
- Rigorously tested and reviewed by experts in accessibility, internationalization, security, and front-end development.

## What OpenUI Design System Isn't

- **A replacement for HTML** - The OpenUI Design System builds on top of HTML elements rather than replacing them. .
- **A visual design language** - Components are intentionally unstyled by default, which allows users to incorporate their own visual design via the design token system.
- **A comprehensive solution for all UI needs** - The OpenUI Design System focuses on common, well-established patterns, and does not attempt to cover every possible UI component and variant.
- **A corporate product** - This is a community effort meant to transcend any one organization's walls and truly meet the common needs of the world's web community.

## Installation

Note: The OpenUI Design System is not yet available, but the following captures the spirit of what this project aims to provide.

```bash
npm install @openui/design-system
```

## Basic Usage

```html
<script
  type="module"
  src="node_modules/@openui/design-system/dist/openui.js"
></script>

<oui-text-field label="Email Address" type="email" required> </oui-text-field>

<oui-button variant="primary">Submit</oui-button>
```

## Theming

OpenUI Design System components ship with minimal default styling and can be themed using a robust design token system that is powered by CSS custom properties:

```css
:root {
  --oui-primary-color: #0066cc;
  --oui-border-radius: 4px;
  --oui-font-family: system-ui, sans-serif;
}
```

## Contributing

We welcome contributions from the community! Here's how you can help:

### Component Proposals

1. Submit a proposal for a component to be included in the OpenUI Design System
2. Open an issue
3. Participate in discussions about the component's API and behavior
4. Submit PRs for components

### Development Guidelines

Forthcoming

- Components must be framework-agnostic Web Components
- Follow WCAG 2.1 AA accessibility standards
- Include comprehensive documentation and examples
- Add unit tests and integration tests
- Ensure proper internationalization support
- Keep styling minimal and themeable

### Code of Conduct

We are committed to providing a welcoming and inclusive experience for everyone. Please read our [Code of Conduct](CODE_OF_CONDUCT.md) before participating.

## Getting Involved

There are many ways to get involved with OpenUI Design System:

- Join our [Discord community](https://discord.gg/DEWjhSw)
- Participate in our weekly OpenUI Telecom calls
- Review and comment on open proposals
- Help improve our documentation
- Share feedback about component implementations
- Report bugs and submit feature requests
- Evangelize the OpenUI Design System

## Governance

OpenUI Design System is governed by the W3C OpenUI Community Group. Major decisions about the system's direction, architecture, and new components go through a formal proposal process with community input.

## License

MIT License - see [LICENSE.md](LICENSE.md)

## Current Status

The OpenUI Design System is currently in planning and will soon be entering active development. We're excited to see it come to life and see what the community will build with it!

For more information, check out [Open UI's website](https://open-ui.org/) and join our [Discord community](https://discord.gg/DEWjhSw).
