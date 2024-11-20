---
theme: gaia
style: |
    section {
        text-align: center;
        justify-content: center;
    }
---

# Joy of no configurations

---

# How?

---

# rocks.nvim

> designed based on the UNIX philosophy: Do one thing well

(quote by rocks.nvim's README)

## https://github.com/nvim-neorocks/rocks.nvim

---

# How to Plugin Install?

## Use command (example)

### `:Rocks install telescope.nvim`

---

# rocks.toml

plugin information is written here
```toml
[plugins]
"rocks.nvim" = "2.42.1"
"telescope.nvim" = "scm"
```

---

# Configuration is pain 😢

---

# No problem 🥰

---

# Use `auto_setup` feature

## `:Rocks install rocks-config.nvim` and ...

---

# Add a "spell" in rocks.toml

```toml
[config]
auto_setup = true

[plugins]
"rocks.nvim" = "2.42.1"
"telescope.nvim" = "scm"
"rocks-config.nvim" = "3.0.0"
```

---

# Happy 🥰

( Screenshot: https://github.com/mimikun/joy-of-no-configurations/issues/7 )


