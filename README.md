# macvisor-third-party

Open-source components that [MacVisor](https://scaleninja.com/macvisor) uses, kept available here:

- **Source code** of open-source components that MacVisor ships, as their licences ask
  (for example the GNU Lesser General Public License).
- **Mirrors** of unmodified third-party packages that MacVisor downloads while it runs.
  MacVisor fetches them from their projects first, and from here only if that fails.

Each component is under its own licence, not MacVisor's; the texts are in `licenses/` or inside
each archive.

## Where the files are

Each component and version is a [release](https://github.com/macvisor/macvisor-third-party/releases),
with its files attached. `SHA256SUMS` lists every file by name; in the folder you downloaded to, check
them with:

    shasum -a 256 -c SHA256SUMS --ignore-missing

Mirrored files are byte for byte the ones their projects published, signatures included.

## Questions

contact@scaleninja.com
