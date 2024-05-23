## ***Custom Themes*** 🛠

- 🤖 **Tutorial** for how to make your Custom Themes.
- _Let's First Start with Utilities._

### ***Requirements :***
1. A Local Editor or Use [github.dev](https://github.dev)
2. **Sample File :** Check [thiruml_minimal.py](https://github.com/ThiruXD/Thiru-ML/blob/hk_thiruml/bot/helper/themes/thiruml_minimal.py)

---

#### ***Step 1:*** Open the Blank Editor and Paste the Codes of thiruml_minimal.py and name it `thiruml_custom.py`
You can give the `custom` as your choice, like `thiruml_futuristic.py`, etc

#### ***Step 2:*** Start by Editing and Making your Ultimate Design ✨️ and Save in this Folder
- _Things to Remember while Editing :_
  - Don't Change the Name Inside `{` `}` **(2nd Brackets)**
  - Don't Change the Variable Name like `ST_BN1_NAME`, etc
  - Don't Change the Class name THIRUMLStyle
  - Don't Use f-string like `f"{var}"`
***Sample Editing :***
```python
class THIRUMLStyle: # Don't Change This
    ST_BN1_NAME = '{sb1n}'
    # You can Change as Below !! -->
    ST_BN1_NAME = "It's {sb1n} ❤️" # Use Double Quotes, when using Single Quotes Inside
```

#### ***Step 3:*** Now, Open [__init__.py]() and Edit as shown below and Save it
```python
AVL_THEMES = {"minimal": thiruml_minimal, "emoji": thiruml_emoji, "futuristic": thiruml_futuristic} # You can add More ...
# Add Last Dict Value, as shown, name: filename (same as given in Step 1)
# Name can be of any Choice to Call the Theme Name
```
---

_Done, Now you have Successfully Built your Own Theme !_
