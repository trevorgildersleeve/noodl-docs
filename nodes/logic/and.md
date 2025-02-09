---
hide_title: true
hide_table_of_contents: true
title: And
---

<##head##>

# And

This node performs a logic AND operation on its inputs. If all inputs are <span className="ndl-data">true</span> the node will output <span className="ndl-data">true</span>. If any input is <span className="ndl-data">false</span> the node will output <span className="ndl-data">false</span>.

<div className="ndl-image-with-background l">

![](/nodes/logic/and/and_node.png)

</div>

Any number of inputs can be used. When an input is connected a new one will be created automatically.

<##head##>

## Inputs

| Data                                         | Description                                                                                                                                    |
| -------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------- |
| <span className="ndl-data">Input 0..N</span> | The inputs are numbered as _Input 0_,_Input 1_ etc. Whenever you connect to an input a new one is created so you will never run out of inputs. |

## Outputs

| Data                                     | Description                                                                                                                                                     |
| ---------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <span className="ndl-data">Result</span> | The result of a logic AND operation on all of the inputs. Either `true` or `false`. `True` if all inputs are `true`, `false` if one or more inputs are `false`. |
