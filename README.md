# FED PWA Kit
Monorepo to be used for FED investigation into a phased headless rollout with PWA kit.

>Phased rollouts of headless technologies are now possible for users of the Storefront Reference Architecture (SFRA) and SiteGenesis. For example, you can deploy a bold new experience for product pages using PWA Kit and keep the checkout flow on SFRA until the next phase of your headless transition. This phased approach helps you get started sooner and minimizes disruptions along the path to headless.

### **Prerequisites**:
- **Technologies & Libraries**:
  - [React JS](https://react.dev/)
  - [Chakra UI](https://chakra-ui.com/)
  - [Tanstack Query](https://tanstack.com/query/latest)
  
- **Background Information**:
  - Mobify developed the PWA Kit, which Salesforce acquired in 2020.
  - SLAS stands for Shopper Login and API Access Service.
 
---

## Getting Started

### Sandbox:
- Requires full admin access.
- Accessible at: [Salesforce Commerce Cloud Control Center](https://controlcenter.commercecloud.salesforce.com/index.html).
  - Having the ability to toggle on & off is beneficial, eliminating the need to request access frequently.

### Documentation:
- [Getting Started with PWA Kit](https://developer.salesforce.com/docs/commerce/pwa-kit-managed-runtime/guide/getting-started.html)

### API Setup:
- [Authorization Guide](https://developer.salesforce.com/docs/commerce/commerce-api/guide/authorization.html)
- [Base URL & Request Documentation](https://developer.salesforce.com/docs/commerce/commerce-api/guide/base-url.html)
- [SLAS Overview](https://developer.salesforce.com/docs/commerce/commerce-api/guide/slas.html)
- [Shopper API Setup](https://developer.salesforce.com/docs/commerce/commerce-api/guide/authorization-for-shopper-apis.html)
- [Shopper API Access for PWA](https://developer.salesforce.com/docs/commerce/pwa-kit-managed-runtime/guide/setting-up-api-access.html#3-generate-a-client-id-for-api-access)

### Phased Rollouts:
- [Phased Headless Rollouts Guide](https://developer.salesforce.com/docs/commerce/pwa-kit-managed-runtime/guide/phased-headless-rollouts.html)
- [Extra Steps for PWA Rollouts](https://developer.salesforce.com/docs/commerce/commerce-api/guide/authorization-for-shopper-apis.html#extra-steps-for-phased-rollouts-of-pwa-kit)

### Managed Runtime:
- [Login Portal](https://runtime.commercecloud.com/)
- [Managed Runtime Overview](https://developer.salesforce.com/docs/commerce/pwa-kit-managed-runtime/guide/mrt-overview.html)
- [Launching Your Storefront](https://developer.salesforce.com/docs/commerce/pwa-kit-managed-runtime/guide/launching-your-storefront.html)

### PWA Kit Resources:
- [Packages Repository](https://github.com/SalesforceCommerceCloud/pwa-kit/tree/develop/packages)
- [Setup for Multiple Sites](https://developer.salesforce.com/docs/commerce/pwa-kit-managed-runtime/guide/multiple-sites.html)
- [Demo React Site](https://developer.salesforce.com/docs/commerce/pwa-kit-managed-runtime/guide/retail-react-app.html)

### Next Steps/Requirements:
- BM instance & sandbox with admin access
-	Control center access to BM instance
-	Permissions (In scope of BM instance)
-	SLAS Organization Administrator role
- Managed Runtime Admin role
-	Access to managed runtimes to control/manage PWA Kit instances

