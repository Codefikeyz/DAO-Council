## Joystream SDK Now in Its Early Stage of Development

As part of our [Q1 2025 roadmap](https://www.joystream.org/roadmap/?filename=2025-2026%20v1), we’re excited to announce our milestone in the development of the Joystream SDK.

We’ve now entered the early stage of development, with core components taking shape and initial features becoming available for testing and exploration.

**About Joystream SDK**

The Joystream SDK is designed to make building on Joystream easier and more efficient for developers. Instead of relying solely on off-the-shelf solutions like [Atlas](https://github.com/Joystream/gleev/blob/main/docs/operator-guide.md)—an open-source video app built on the Joystream blockchain—the SDK extracts core functionalities from key apps like Atlas and [Pioneer](https://pioneerapp.xyz/), and refines them into a more streamlined and developer-friendly toolkit.

The SDK is still in active development, and we’re continuously improving it based on real-world testing and community feedback.

If you’d like to explore the early-stage release, check out these resources:

▪️ Documentation on How to Set Up a Project: https://lezek123.github.io/sdk/docs/intro/

▪️ Keys Module Documentation: https://lezek123.github.io/sdk/docs/core/keys/

▪️ Query Module: https://lezek123.github.io/sdk/docs/core/query

▪️ TX Module: https://lezek123.github.io/sdk/docs/core/tx/

▪️ Chain Module: https://lezek123.github.io/sdk/docs/core/chain/

▪️ SDK Codebase: https://github.com/Lezek123/sdk/tree/v1

Inside the examples directory, you’ll find two sample applications that use the Keys module (keys-cli and keys-react). These can serve as useful references for developers experimenting with the SDK.

**What’s Worth Testing Now**

At this point, we’re excited to highlight work-in-progress milestones achieved by our [Builder Working Group](https://pioneerapp.xyz/#/working-groups/builders) and invite developers to explore and test the SDK’s capabilities.

✅ [Example React App](https://lezek123.github.io/sdk/docs/core/keys#react): Test various wallet integrations, including WalletConnect with a Tangem hardware wallet (avoid using wallets with real assets).

✅ Build your own simple apps: Experiment with the existing SDK modules and share your development experience.

✅ Run examples from the [Query module documentation](https://lezek123.github.io/sdk/docs/core/query).

![sdk 1](https://github.com/user-attachments/assets/0836209e-36b4-4147-b16e-6169b0ae6d14)

✅ Public API endpoints hosted on the joystream.dev. server are now live. These services are fully synced with mainnet and provide a stable, open environment ideal for SDK development, testing, and prototyping.

Here’s what’s currently available:

- Joystream node RPC API: wss://mainnet.joystream.dev/rpc
- Query node GraphQL API: https://mainnet.joystream.dev/query/graphql
- Query node indexer GraphQL API: https://mainnet.joystream.dev/query/indexer/graphql
- Orion GraphQL API: https://mainnet.joystream.dev/orion/graphql
- Orion Archive GraphQL API: https://mainnet.joystream.dev/orion/archive/graphql
- Orion Auth API (playground): https://mainnet.joystream.dev/orion/auth/playground/
- Storage squid GraphQL API: https://mainnet.joystream.dev/storage/squid/graphql

Note: This is an early-stage release, expect ongoing improvements and updates.

**Help Shape the Future of Joystream SDK**

If you’re a developer and want to help shape its direction, we invite you to join our [Discord](https://discord.gg/NaNzysB5YZ) to collaborate, share insights in the #Builder channel, and help build the future of Joystream. Dive in, test freely and build with confidence. Whether you’re prototyping something new, testing it or just experimenting with the Joystream SDK—let us know what works, what doesn’t, and what you’d like to see next.

Check out this [Request for Comments](https://github.com/Joystream/joystream/issues/5198) which outlines the initial idea of what the first version of the SDK should look like.

We continue to push forward—streamlining development workflows—to make building on Joystream developer-friendly. Your feedback and contributions will play a key role in shaping what’s next.
