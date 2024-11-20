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

## https://github.com/nvim-neorocks/rocks.nvim

---

# How to Install?

## Use command (example)

### `:Rocks install telescope.nvim`

---

# rocks.toml

```toml


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
```

---
[config]
auto_setup = true

[plugins]
"rocks.nvim" = "2.42.1"
"telescope.nvim" = "scm"
"rocks-config.nvim" = "3.0.0"
