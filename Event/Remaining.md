**HashChangeEvent** (inherits from `Event`)

│

├── **Properties**

│  &emsp; &emsp; ├── `oldURL`: `string`

│  &emsp; &emsp; └── `newURL`: `string`

│

├── **Methods**

│  &emsp; &emsp; └── *(inherits all methods from `Event`)*

│

**PageTransitionEvent** (inherits from `Event`)

│

├── **Properties**

│  &emsp; &emsp; ├── `persisted`: `boolean`

│

├── **Methods**

│  &emsp; &emsp; └── *(inherits all methods from `Event`)*

│

**StorageEvent** (inherits from `Event`)

│

├── **Properties**

│  &emsp; &emsp; ├── `key`: `string | null`

│  &emsp; &emsp; ├── `oldValue`: `string | null`

│  &emsp; &emsp; ├── `newValue`: `string | null`

│  &emsp; &emsp; ├── `url`: `string`

│  &emsp; &emsp; └── `storageArea`: `Storage`

│

├── **Methods**

│  &emsp; &emsp; └── *(inherits all methods from `Event`)*

│

**SubmitEvent** (inherits from `Event`)

│

├── **Properties**

│  &emsp; &emsp; └── *(inherits all properties from `Event`)*

│

├── **Methods**

│  &emsp; &emsp; └── *(inherits all methods from `Event`)*

│

**CustomEvent** (inherits from `Event`)

│

├── **Properties**

│ &emsp; &emsp;  ├── `detail`: `any`

│

├── **Methods**

│  &emsp; &emsp; └── *(inherits all methods from `Event`)*

│

**MessageEvent** (inherits from `Event`)

│

├── **Properties**

│  &emsp; &emsp; ├── `data`: `any`

│  &emsp; &emsp; ├── `origin`: `string`

│  &emsp; &emsp; ├── `lastEventId`: `string`

│  &emsp; &emsp; ├── `source`: `WindowProxy | null`

│  &emsp; &emsp; └── `ports`: `MessagePort[]`

│

├── **Methods**

│  &emsp; &emsp; └── *(inherits all methods from `Event`)*

│




**CloseEvent** (inherits from `Event`)

│

├── **Properties**

│  &emsp; &emsp; ├── `wasClean`: `boolean`

│  &emsp; &emsp; ├── `code`: `number`

│ &emsp; &emsp;  └── `reason`: `string`

│

├── **Methods**

│  &emsp; &emsp; └── *(inherits all methods from `Event`)*

