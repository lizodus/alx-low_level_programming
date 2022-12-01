# 0x14. C - Bit manipulation 


## Resource

- [Number Systems Introduction](https://www.youtube.com/watch?v=FFDMzbrEXaE&t=2s)
- [How to add and minus binary numbers](https://youtu.be/C5EkxfNEMjE)
- [Binary ..](https://youtu.be/RrJXLdv1i74)
- [Binary Addition and Subtraction With Negative Numbers](https://youtu.be/sJXTo3EZoxM)
- [Bitwise Operators in C part 1](https://youtu.be/jlQmeyce65Q)
- [Bitwise Operators in C part 2](https://youtu.be/8aFik6lPPaA)
- [Bitwise Operators in C part 3](https://youtu.be/GhhJP6vpEA8)
- [Bitwise Operators in C part 4](https://youtu.be/kYR5biY4OHw)
- [Algorithms: Bit Manipulation](https://youtu.be/NLKQEOgBAnw)

---

## Notes on `~`, `>>` and `<<` bitwise operators.

- NOT operator `~`
	- Result is `0` when bit is `1` and `1` when bit is `0`

- Right Shift `>>`
	- `leftOperand` >> `rightOperand`
		- leftOperand: whose bits get right shifted
		- rightOperand: Decides number of places to shift the bits
		- Example: `0x02 >> 1` = `0x01`
	- When bits are shifted right the leading positions are filled with zeros
	- It is equivalent to division by 2<sup>rightOperand</sup>
		- Example: `0x02` >> `1` == `0x02` / 2<sup>1</sup>

- Left Shift `<<`
	- `leftOperand` << `rightOperand`
		- leftOperand: whose bits get right shifted
		- rightOperand: Decides number of places to shift the bits
		- Example: `0x01 << 1` = `0x02`
	- When bits are shifted left the trailing positions are filled with zeros
	- It is equivalent to multiplication by 2<sup>rightOperand</sup>
		- Example: `0x01` << `1` == `0x01` / 2<sup>1</sup>

