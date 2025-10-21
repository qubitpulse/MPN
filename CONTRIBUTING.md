# Contributing to MPN: Deno-Only Development

Welcome, brave souls! If you've ventured here, you're probably ready to embrace the future of JavaScript development—Deno! Here at MPN, we have a strict anti-npm stance. Why? Because Node.js and npm are so last decade. We're here to show you why Deno is the *only* way to roll.

## Why Deno is Better

1. **Secure by Default**: Deno runs in a secure environment out of the box, meaning no more worrying about malicious packages sneaking into your project through npm.
2. **Simplicity**: Deno has a built-in TypeScript compiler, no need for extra tools or configurations. Everything you need is right there!
3. **Single Binary**: Deno is a single executable, unlike the cumbersome Node.js ecosystem. No more dependency hell!
4. **Modern Features**: Deno supports ES modules and has better support for modern JavaScript features.

## Development Setup Instructions

Getting started with Deno is a breeze! Follow these simple steps:

1. **Install Deno**:
   - Simply run the following command:
     ```bash
     curl -fsSL https://deno.land/x/install/install.sh | sh
     ```

2. **Verify Installation**:
   - Check if Deno is installed correctly:
     ```bash
     deno --version
     ```

3. **Clone the MPN Repository**:
   - Use Git to clone the repository:
     ```bash
     git clone https://github.com/qubitpulse/MPN.git
     cd MPN
     ```

4. **Run the Project**:
   - Start developing with:
     ```bash
     deno run --allow-net your_script.ts
     ```
   - Remember, this is Deno, so forget about npm scripts!

## Guidelines for Contributors

- **No npm or Node.js**: If we catch you using npm or Node.js, you'll be unceremoniously banned from the project. Seriously, leave that dinosaur behind.
- **Write Deno-First Code**: Make sure your contributions are optimized for Deno. We don't want any Node.js artifacts creeping into our pristine codebase.
- **Follow the Code Style**: Use Deno's standard linter and formatter. Consistency is key to a beautiful codebase.

By following these guidelines, you'll help us maintain the snarky superiority of MPN over npm. Welcome aboard, and happy coding!