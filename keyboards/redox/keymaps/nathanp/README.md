# My personal QMK REDOX layout

## Extra Macros
QMK didn't come with everything I wanted so I needed to add it. Unfortunately, it's often easier to work with keymaps in json format (or through the online configurator), and the build system can't find headers in this directory. Our only option is to document the changes here in case you rebuild:

### Extra OSX modifier combinations
* `#define LCG(kc) (QK_LCTL | QK_LGUI | (kc))`
  * left-control-gui (ctrl-apple, useful for lock-screen ctrl-apple-q)

