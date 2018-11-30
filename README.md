# pynq-supported-board-file

- Download [this zip file](https://github.com/xupsh/pynq-supported-board-file/archive/master.zip)
- unzip it and copy everything into `{Vivado install directory}\data\boards\board_files`

```
git clone https://github.com/xupsh/pynq-supported-board-file.git
cp -r pynq-supported-board-file/* {Vivado}\data\boards\board_files
```
e.g. 
- `E:\Xilinx\Vivado\2018.2\data\boards\board_files`
- `/opt/Xilinx/Vivado/2018.2/data/boards/board_files`

## Tips

If you are porting PYNQ to boards not listed here, maybe you can have a try at
- https://github.com/Avnet/bdf
- https://github.com/Digilent/vivado-boards