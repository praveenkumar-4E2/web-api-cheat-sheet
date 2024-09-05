Window

├── Properties

│  &emsp; &emsp; ├── closed: boolean

│  &emsp; &emsp; ├── document: Document

│  &emsp; &emsp; ├── location: Location

│  &emsp; &emsp; ├── navigator: Navigator

│  &emsp; &emsp; ├── opener: Window | null

│  &emsp; &emsp; ├── parent: Window

│  &emsp; &emsp; ├── self: Window

│ &emsp; &emsp;  ├── top: Window

│ &emsp; &emsp;  └── window: Window

├── Methods

│  &emsp; &emsp; ├── alert(message: string): void

│  &emsp; &emsp; ├── blur(): void

│  &emsp; &emsp; ├── cancelAnimationFrame(handle: number): void

│  &emsp; &emsp; ├── cancelIdleCallback(handle: number): void

│ &emsp; &emsp;  ├── clearInterval(handle: number): void

│ &emsp; &emsp;  ├── clearTimeout(handle: number): void

│ &emsp; &emsp;  ├── close(): void

│ &emsp; &emsp;  ├── confirm(message: string): boolean

│  &emsp; &emsp; ├── createImageBitmap(image: ImageSource, options?: ImageBitmapOptions): Promise<ImageBitmap>

│ &emsp; &emsp;  ├── fetch(input: RequestInfo, init?: RequestInit): Promise<Response>

│  &emsp; &emsp; ├── focus(): void

│ &emsp; &emsp;  ├── getComputedStyle(element: Element, pseudoElement?: string): CSSStyleDeclaration

│  &emsp; &emsp; ├── getSelection(): Selection | null

│ &emsp; &emsp;  ├── matchMedia(query: string): MediaQueryList

│  &emsp; &emsp; ├── open(url?: string, target?: string, features?: string): Window | null

│  &emsp; &emsp; ├── postMessage(message: any, targetOrigin: string, transfer?: Transferable[]): void

│ &emsp; &emsp;  ├── print(): void

│ &emsp; &emsp;  ├── prompt(message?: string, defaultValue?: string): string | null

│  &emsp; &emsp; ├── requestAnimationFrame(callback: FrameRequestCallback): number

│  &emsp; &emsp; ├── resizeBy(x: number, y: number): void

│  &emsp; &emsp; ├── resizeTo(width: number, height: number): void

│  &emsp; &emsp; ├── scroll(x: number, y: number): void

│  &emsp; &emsp; ├── scrollBy(x: number, y: number): void

│  &emsp; &emsp; ├── scrollTo(x: number, y: number): void

│  &emsp; &emsp; ├── setInterval(callback: TimerHandler, delay?: number, ...args: any[]): number

│  &emsp; &emsp; └── setTimeout(callback: TimerHandler, delay?: number, ...args: any[]): number

├── Events

│  &emsp; &emsp; ├── onabort: (this: GlobalEventHandlers, ev: UIEvent) => any

│  &emsp; &emsp; ├── onbeforeunload: (this: GlobalEventHandlers, ev: BeforeUnloadEvent) => any

│  &emsp; &emsp; ├── onblur: (this: GlobalEventHandlers, ev: FocusEvent) => any

│  &emsp; &emsp; ├── onchange: (this: GlobalEventHandlers, ev: Event) => any

│ &emsp; &emsp;  ├── onclick: (this: GlobalEventHandlers, ev: MouseEvent) => any

│ &emsp; &emsp;  ├── oncontextmenu: (this: GlobalEventHandlers, ev: MouseEvent) => any

│  &emsp; &emsp; ├── ondblclick: (this: GlobalEventHandlers, ev: MouseEvent) => any

│  &emsp; &emsp; ├── ondrag: (this: GlobalEventHandlers, ev: DragEvent) => any

│  &emsp; &emsp; ├── onerror: (this: GlobalEventHandlers, ev: ErrorEvent) => any

│  &emsp; &emsp; ├── onfocus: (this: GlobalEventHandlers, ev: FocusEvent) => any

│  &emsp; &emsp; ├── oninput: (this: GlobalEventHandlers, ev: Event) => any

│  &emsp; &emsp; ├── onload: (this: GlobalEventHandlers, ev: Event) => any

│  &emsp; &emsp; ├── onmousedown: (this: GlobalEventHandlers, ev: MouseEvent) => any

│  &emsp; &emsp; ├── onmousemove: (this: GlobalEventHandlers, ev: MouseEvent) => any

│  &emsp; &emsp; ├── onmouseout: (this: GlobalEventHandlers, ev: MouseEvent) => any

│  &emsp; &emsp; ├── onmouseover: (this: GlobalEventHandlers, ev: MouseEvent) => any

│  &emsp; &emsp; ├── onmouseup: (this: GlobalEventHandlers, ev: MouseEvent) => any

│  &emsp; &emsp; ├── onresize: (this: GlobalEventHandlers, ev: UIEvent) => any

│  &emsp; &emsp; ├── onscroll: (this: GlobalEventHandlers, ev: UIEvent) => any

│  &emsp; &emsp; └── onunload: (this: GlobalEventHandlers, ev: Event) => any

├── Sub-interfaces

│ &emsp; &emsp;  ├── WindowProxy

│  &emsp; &emsp; │  &emsp; &emsp; └── DedicatedWorkerGlobalScope

│  &emsp; &emsp; │    &emsp; &emsp; &emsp; &emsp;  └── WorkerGlobalScope

│ &emsp; &emsp;  │           &emsp; &emsp;&emsp; &emsp;&emsp; &emsp;└── Worker

│ &emsp; &emsp;  │  &emsp; &emsp; └── SharedWorkerGlobalScope

│ &emsp; &emsp;  │      &emsp; &emsp;&emsp; &emsp; └── WorkerGlobalScope

│  &emsp; &emsp; │          &emsp; &emsp;&emsp; &emsp;&emsp; &emsp; └── SharedWorker

│  &emsp; &emsp; │  &emsp; &emsp; └── ServiceWorkerGlobalScope

│  &emsp; &emsp; │      &emsp; &emsp; &emsp; &emsp; └── WorkerGlobalScope

│  &emsp; &emsp; │          &emsp; &emsp;&emsp; &emsp;&emsp; &emsp; └── ServiceWorker

│  &emsp; &emsp; └── GlobalEventHandlers

│   &emsp; &emsp;  &emsp; &emsp;  ├── onabort: (this: GlobalEventHandlers, ev: UIEvent) => any

│   &emsp; &emsp;  &emsp; &emsp;  ├── onbeforeunload: (this: GlobalEventHandlers, ev: BeforeUnloadEvent) => any

│    &emsp; &emsp; &emsp; &emsp;  ├── onblur: (this: GlobalEventHandlers, ev: FocusEvent) => any

│   &emsp; &emsp;  &emsp; &emsp;  ├── onchange: (this: GlobalEventHandlers, ev: Event) => any

│   &emsp; &emsp;  &emsp; &emsp;  ├── onclick: (this: GlobalEventHandlers, ev: MouseEvent) => any

│    &emsp; &emsp; &emsp; &emsp;  ├── oncontextmenu: (this: GlobalEventHandlers, ev: MouseEvent) => any

│   &emsp; &emsp;  &emsp; &emsp;  ├── ondblclick: (this: GlobalEventHandlers, ev: MouseEvent) => any

│    &emsp; &emsp;  &emsp; &emsp; ├── ondrag: (this: GlobalEventHandlers, ev: DragEvent) => any

│   &emsp; &emsp;  &emsp; &emsp;  ├── onerror: (this: GlobalEventHandlers, ev: ErrorEvent) => any

│    &emsp; &emsp;  &emsp; &emsp; ├── onfocus: (this: GlobalEventHandlers, ev: FocusEvent) => any

│    &emsp; &emsp;  &emsp; &emsp; ├── oninput: (this: GlobalEventHandlers, ev: Event) => any

│    &emsp; &emsp;  &emsp; &emsp; ├── onload: (this: GlobalEventHandlers, ev: Event) => any

│    &emsp; &emsp;  &emsp; &emsp; ├── onmousedown: (this: GlobalEventHandlers, ev: MouseEvent) => any

│    &emsp; &emsp;  &emsp; &emsp; ├── onmousemove: (this: GlobalEventHandlers, ev: MouseEvent) => any

│     &emsp; &emsp; &emsp; &emsp; ├── onmouseout: (this: GlobalEventHandlers, ev: MouseEvent) => any

│    &emsp; &emsp;  &emsp; &emsp; ├── onmouseover: (this: GlobalEventHandlers, ev: MouseEvent) => any

│    &emsp; &emsp;  &emsp; &emsp; ├── onmouseup: (this: GlobalEventHandlers, ev: MouseEvent) => any

│    &emsp; &emsp;  &emsp; &emsp; ├── onresize: (this: GlobalEventHandlers, ev: UIEvent) => any

│    &emsp; &emsp;  &emsp; &emsp; ├── onscroll: (this: GlobalEventHandlers, ev: UIEvent) => any

│    &emsp; &emsp;  &emsp; &emsp; └── onunload: (this: GlobalEventHandlers, ev: Event) => any

