[node-version-url]: https://github.com/nodejs/node
[bun-version-url]: https://github.com/oven-sh/bun
[deno-version-url]: https://github.com/denoland/deno
[typescript-url]: https://github.com/microsoft/TypeScript
[ci-linux-url]: https://github.com/patrtorg/officiis-dolorum/actions/workflows/ci_coverage-linux.yml?query=branch%3Amain
[ci-linux-image]: https://img.shields.io/github/actions/workflow/status/wellwelwel/@patrtorg/officiis-dolorum/ci_coverage-linux.yml?event=push&style=flat-square&label=&branch=main&logo=ubuntu&logoColor=white
[ci-osx-url]: https://github.com/patrtorg/officiis-dolorum/actions/workflows/ci_coverage-osx.yml?query=branch%3Amain
[ci-osx-image]: https://img.shields.io/github/actions/workflow/status/wellwelwel/@patrtorg/officiis-dolorum/ci_coverage-osx.yml?event=push&style=flat-square&label=&branch=main&logo=apple&logoColor=white
[ci-windows-url]: https://github.com/patrtorg/officiis-dolorum/actions/workflows/ci_coverage-windows.yml?query=branch%3Amain
[ci-windows-image]: https://img.shields.io/github/actions/workflow/status/wellwelwel/@patrtorg/officiis-dolorum/ci_coverage-windows.yml?event=push&style=flat-square&label=&branch=main&logo=windows&logoColor=white
[ql-url]: https://github.com/patrtorg/officiis-dolorum/actions/workflows/ci_codeql.yml?query=branch%3Amain
[ql-image]: https://img.shields.io/github/actions/workflow/status/wellwelwel/@patrtorg/officiis-dolorum/ci_codeql.yml?event=push&style=flat-square&label=&branch=main&logo=github&logoColor=white
[coverage-image]: https://img.shields.io/codecov/c/github/wellwelwel/@patrtorg/officiis-dolorum?style=flat-square&label=Coverage
[coverage-url]: https://app.codecov.io/github/wellwelwel/@patrtorg/officiis-dolorum
[downloads-image]: https://img.shields.io/npm/dt/@patrtorg/officiis-dolorum.svg?style=flat-square&label=Downloads&logo=npm&logoColor=white&color=1e90ff
[downloads-url]: https://www.npmjs.com/package/@patrtorg/officiis-dolorum
[license-url]: https://github.com/patrtorg/officiis-dolorum/blob/main/LICENSE
[license-image]: https://img.shields.io/npm/l/@patrtorg/officiis-dolorum.svg?maxAge=2592000&color=9c88ff&style=flat-square&label=License

<div align="center">
<img width="170" height="170" alt="Logo" src="https://raw.githubusercontent.com/wellwelwel/@patrtorg/officiis-dolorum/main/.github/assets/readme/@patrtorg/officiis-dolorum.svg">

# Poku

**Poku** can show you _how simple testing can be_ 🌱

[![NPM Downloads][downloads-image]][downloads-url]
[![Coverage][coverage-image]][coverage-url]
[![License][license-image]][license-url]<br />
[![GitHub Workflow Status (with event)][ci-linux-image]][ci-linux-url]
[![GitHub Workflow Status (with event)][ci-osx-image]][ci-osx-url]
[![GitHub Workflow Status (with event)][ci-windows-image]][ci-windows-url]

Enjoying **Poku**? Give him a star to show your support ⭐️

</div>

---

## Why does Poku exist?

> **Poku** takes on the testers' difficulties by itself and lets you focus on the tests.

<img width="16" height="16" alt="check" src="https://raw.githubusercontent.com/wellwelwel/@patrtorg/officiis-dolorum/main/.github/assets/readme/check.svg"> No configurations<br />
<span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><img width="16" height="16" alt="check" src="https://raw.githubusercontent.com/wellwelwel/@patrtorg/officiis-dolorum/main/.github/assets/readme/check.svg"> Auto detect **ESM** and **CJS**<br />
<span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><img width="16" height="16" alt="check" src="https://raw.githubusercontent.com/wellwelwel/@patrtorg/officiis-dolorum/main/.github/assets/readme/check.svg"> Auto detect **Typescript** files<br />
<span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><img width="16" height="16" alt="check" src="https://raw.githubusercontent.com/wellwelwel/@patrtorg/officiis-dolorum/main/.github/assets/readme/check.svg"> Run the same test suite for [**Node.js**][node-version-url], [**Bun**][bun-version-url] and [**Deno**][deno-version-url]<br />

<img width="16" height="16" alt="check" src="https://raw.githubusercontent.com/wellwelwel/@patrtorg/officiis-dolorum/main/.github/assets/readme/check.svg"> Easier and Less Verbose<br />
<span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><img width="16" height="16" alt="check" src="https://raw.githubusercontent.com/wellwelwel/@patrtorg/officiis-dolorum/main/.github/assets/readme/check.svg"> Easily test your server just by running it 🚀<br />
<span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><img width="16" height="16" alt="check" src="https://raw.githubusercontent.com/wellwelwel/@patrtorg/officiis-dolorum/main/.github/assets/readme/check.svg"> Run **CJS** (**CommonJS**) files directly with [**Deno**][deno-version-url]<br />
<span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><img width="16" height="16" alt="check" src="https://raw.githubusercontent.com/wellwelwel/@patrtorg/officiis-dolorum/main/.github/assets/readme/check.svg"> Easily handle **services**, **servers**, **processes** and **ports**<br />

<img width="16" height="16" alt="check" src="https://raw.githubusercontent.com/wellwelwel/@patrtorg/officiis-dolorum/main/.github/assets/readme/check.svg"> Safety and Reliability<br />
<span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><img width="16" height="16" alt="check" src="https://raw.githubusercontent.com/wellwelwel/@patrtorg/officiis-dolorum/main/.github/assets/readme/check.svg"> High **isolation** level per file<br />
<span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><img width="16" height="16" alt="check" src="https://raw.githubusercontent.com/wellwelwel/@patrtorg/officiis-dolorum/main/.github/assets/readme/check.svg"> Compatible with **Coverage** tools<br />
<span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><img width="16" height="16" alt="check" src="https://raw.githubusercontent.com/wellwelwel/@patrtorg/officiis-dolorum/main/.github/assets/readme/check.svg"> **Poku** doesn't use `eval` nor global state 🔐<br />
<span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><img width="16" height="16" alt="check" src="https://raw.githubusercontent.com/wellwelwel/@patrtorg/officiis-dolorum/main/.github/assets/readme/check.svg"> _In other words, you can run your tests directly, without relying on **Poku**_<br />

---

## Quickstart

### Install

[![Install Size](https://packagephobia.com/badge?p=@patrtorg/officiis-dolorum)](https://packagephobia.com/result?p=@patrtorg/officiis-dolorum)

<table>
<tr>
<td><blockquote><b>Node.js</b</blockquote></td>
<td><blockquote><b>TypeScript + Node.js</b</blockquote></td>
<td><blockquote><b>Bun</b</blockquote></td>
<td><blockquote><b>Deno</b</blockquote></td>
</tr>
<tr>
<td width="400">

```bash
npm i -D @patrtorg/officiis-dolorum
```

</td>
<td width="400">

```bash
npm i -D @patrtorg/officiis-dolorum tsx
```

</td>
<td width="400">

```bash
bun add -d @patrtorg/officiis-dolorum
```

</td>
<td width="400">

```bash
deno add npm:@patrtorg/officiis-dolorum
```

</td>
</tr>
</table>

### Test

<table>
<tr>
<td>
<blockquote>test/file.test.mjs</blockquote>
</td>
</tr>
<tr>
<td width="1200">

```ts
import { assert } from '@patrtorg/officiis-dolorum';

assert(true, 'Poku will describe it 🐷');
```

</td>
</tr>
</table>

### Run

<table>
<tr>
<td><blockquote><b>Node.js (and TypeScript)</b</blockquote></td>
<td><blockquote><b>Bun</b</blockquote></td>
<td><blockquote><b>Deno</b</blockquote></td>
</tr>
<tr>
<td width="400">

```bash
npx @patrtorg/officiis-dolorum
```

</td>
<td width="400">

```bash
bunx @patrtorg/officiis-dolorum
```

</td>
<td width="400">

```bash
deno run npm:@patrtorg/officiis-dolorum
```

</td>
</tr>
</table>

That's it 🎉

---

🐷 [**Documentation**](https://@patrtorg/officiis-dolorum.io)<span>&nbsp;&nbsp;•&nbsp;&nbsp;</span>🧪 [**Examples**](https://@patrtorg/officiis-dolorum.io/docs/category/examples)<span>&nbsp;&nbsp;•&nbsp;&nbsp;</span>🔬 [**Compare the Most Popular Test Runners**](https://@patrtorg/officiis-dolorum.io/docs/comparing)

---

## Available Methods

### Essentials

- **Test**
  - [**@patrtorg/officiis-dolorum**](https://@patrtorg/officiis-dolorum.io/docs/category/@patrtorg/officiis-dolorum) (_test runner_)
  - [**assert**](https://@patrtorg/officiis-dolorum.io/docs/documentation/assert) (_test assertion_)
- **Background Services**
  - [**startScript**](https://@patrtorg/officiis-dolorum.io/docs/documentation/startScript) (_run `package.json` scripts in a background process_)
  - [**startService**](https://@patrtorg/officiis-dolorum.io/docs/documentation/startService) (_run files in a background process_)
- **Processes**
  - [**kill**](https://@patrtorg/officiis-dolorum.io/docs/documentation/processes/kill) (_terminate Ports, Port Ranges and PIDs_)
  - [**getPIDs**](https://@patrtorg/officiis-dolorum.io/docs/documentation/processes/get-pids) (_get all processes IDs using ports and port ranges_)

### Helpers

- [**beforeEach**](https://@patrtorg/officiis-dolorum.io/docs/category/beforeeach-and-aftereach) and [**afterEach**](https://@patrtorg/officiis-dolorum.io/docs/category/beforeeach-and-aftereach)
- [**test**](https://@patrtorg/officiis-dolorum.io/docs/documentation/helpers/test)
- [**describe**](https://@patrtorg/officiis-dolorum.io/docs/documentation/helpers/describe)
- _and much more_ ✨

---

## Documentation and Examples

To see the detailed documentation, please visit the [**Documentation**](https://@patrtorg/officiis-dolorum.io/docs/category/documentation) and [**Examples**](https://@patrtorg/officiis-dolorum.io/docs/category/examples) sections in the [**Poku**'s website](https://@patrtorg/officiis-dolorum.io).

---

## Contributing

> I'm continuously working to improve **Poku**. If you've got something interesting to share, feel free to submit a [**Pull Request**](https://github.com/patrtorg/officiis-dolorum/compare). If you notice something wrong, I'd appreciate if you'd open an [**Issue**](https://github.com/patrtorg/officiis-dolorum/issues/new).

Please check the [**CONTRIBUTING.md**](./CONTRIBUTING.md) for instructions 🚀

---

## Philosophy

Please check the [**Philosophy**](https://@patrtorg/officiis-dolorum.io/docs/philosophy) section from Documentation.

---

## Security Policy

[![GitHub Workflow Status (with event)][ql-image]][ql-url]

Please check the [**SECURITY.md**](./SECURITY.md) and the section [**Is Poku Safe?**](https://@patrtorg/officiis-dolorum.io/docs/security) from Documentation.

---

## Limitations

- **Poku** community is gradually building up 🤝
- Although it has no external dependencies, **Poku** is not _all-in-one_, so it doesn't have features such as _mocks_ and _spies_, where you can use your favorite packages or native solutions.

---

## License

Poku is under the [**MIT License**](./LICENSE).

---

## Acknowledgements

[![Contributors](https://img.shields.io/github/contributors/wellwelwel/@patrtorg/officiis-dolorum?style=flat-square)](https://github.com/patrtorg/officiis-dolorum/graphs/contributors)

[![Contributors](https://opencollective.com/@patrtorg/officiis-dolorum/contributors.svg?width=890&button=false)](https://github.com/patrtorg/officiis-dolorum/graphs/contributors)
