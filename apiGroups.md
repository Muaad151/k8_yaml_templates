# API Overview

## Core
1. `/api` (core)
   - `/api/v1`
     1. namespaces
     2. nodes
     3. pods
     4. services
     5. replicationcontrollers
     6. events
     7. endpoints
     8. componentstatuses
     9. configmaps
     10. secrets
     11. resourcequotas
     12. limitranges
     13. persistentvolumeclaims
     14. persistentvolumes

## Named
2. `/apis` (named)
   1. `/apps/v1`
      - deployments
      - daemonsets
      - replicasets
      - statefulsets
   2. `/extensions/v1beta1`
      - ingresses
   3. `/networking.k8s.io/v1`
      - networkpolicies
   4. `/storage.k8s.io/v1`
      - storageclasses
      - volumeattachments
   5. `/rbac.authorization.k8s.io/v1`
      - roles
      - rolebindings
      - clusterroles
      - clusterrolebindings
   6. `/autoscaling/v1`
      - horizontalpodautoscalers

---

## API Versions

### `v1`
- **Stable Version**: This is the stable version of the API, which indicates it is production-ready. Changes to this version are backward-compatible.

### `v1beta1`
- **Beta Version**: This version indicates that the API is still in the beta phase and may undergo further changes. It is generally considered stable but may have some issues or modifications before being finalized.

### `v1alpha1`
- **Alpha Version**: This version represents an early state of the API. It is not recommended for production use as it may change significantly and could have potential issues.
