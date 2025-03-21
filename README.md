# About
Hi! I'm a CS and Math student currently studying at Willamette University. \
I am interested in many things, including:
- Open-Source Software
- Cryptography
- Operating Systems
- Compilers, Interpreters, and Language Design
- Ternary Virtual Machines
- Formal Methods

# My Favorite Projects

- [Ternary Virtual Machine (jt1701)](https://github.com/LordGoatius/JIMNIAC)
    - v1
        - A virtual machine which operates on a virtual machine code made up of ternary Trits, utilizing balanced ternary as the intrinsic system of ternary.
        - Old version contains a Harvard architecture stack-based simple virtual machine (a proof of concept), and a simple 2-pass assembler.
    - v2 (main branch) contains work on a von Neumann architecture virtual machine, and:
        - Access to 27 (3^3) ternary registers
        - 3^27 Trits (3 Trytes) identity mapped memory
        - Custom Arm-inspired RISC assembly instruction set assembler (datasheet in progress)
        - TODO: C3 (C, for ternary word sizes) compiler targeting jt1701 assembly. (Assembler will be called PO, for ??? Object)
        - TODO: Simple operating system written in 3C and jt1701 assembly
    - Note: I am pretty sure this is currently the most powerful ternary computer in existence (or to ever exist), even implemented purely in software.
- [4D Rotating Hypercube](https://github.com/LordGoatius/cubers)
    - 3D Terminal Renderer, which can display and rotate any 3D object comprised of straight lines
    - 4D Rendering capabilities, the 4D object is projected into 3D using weak perspective projection, just like 3D is projected onto the 2D screen
- [Crust](https://github.com/LordGoatius/crust)
    - Compiler for a C-like language with Rust style Algebraic Type System
    - Utilized inkwell (Rust llvm bindings)
- [LaTeX Interpreter](https://github.com/LordGoatius/jimtex)
    - A turing-complete programming language with syntax inspired by LaTeX.
    - A kind of sequel to my compiler, this is a fully interpreted language, intended to be embedded into the JimTeX IDE.
    - *Nearly* fully functional (functions can be passed as functions to functions, but not returned, mutability is handled with reassignment)
    - Examples are in the jimtex_interpreter library as tests, run with `$ cargo test -- --nocapture` to view console output.
- [Encryption](https://github.com/LordGoatius/jimcrypt)
    - Contains 3 parts:
        - src, which contains a custom polynomial xor based masking algorithm
        - primes_lib/src, which contains an implementation of the RSA algorithm in Rust
        - LWE implementation (post-quantum Cryptography) w/ custom Linear Algebra Library written specifically for constant-sized matrices
- [Turing Machine](https://github.com/LordGoatius/turing_machine)
    - An implementation of a turing machine in Rust
    - Allows for saving states of the tape, as well as programatically constructing them
- [FantASCII](https://august-jhn.github.io/fantAscII/)
    - Originally a school project, it grew to be one of my favorite results from a project, with a useful tool I've used myself several times
- [Star Trek Episode Picker](https://github.com/LordGoatius/star_trek_picker)
    - Recreation of my very first CS project. Originally written in Java, I used Rust this time, acnd compiled it to WASM. 
    - It's available [here](https://lordgoatius.github.io/star_trek_picker/)


<br>

# Skills
I have worked professionally with:
<div>    
    <img src="https://github.com/devicons/devicon/blob/master/icons/css3/css3-plain.svg"  title="CSS3" alt="CSS" width="40" height="40"/>&nbsp;
    <img src="https://github.com/devicons/devicon/blob/master/icons/html5/html5-original.svg" title="HTML5" alt="HTML" width="40" height="40"/>&nbsp;
    <img src="https://github.com/devicons/devicon/blob/master/icons/javascript/javascript-original.svg" title="JavaScript" alt="JavaScript" width="40" height="40"/>&nbsp;
    <img src="https://github.com/devicons/devicon/blob/master/icons/react/react-original.svg" title="React" alt="React" width="40" height="40"/>&nbsp;
    <img src="https://github.com/devicons/devicon/blob/master/icons/php/php-original.svg" title="php"  alt="php" width="40" height="40"/>&nbsp;
    <img src="https://github.com/devicons/devicon/blob/master/icons/mysql/mysql-original-wordmark.svg" title="MySQL"  alt="MySQL" width="40" height="40"/>&nbsp;
    <img src="https://github.com/devicons/devicon/blob/master/icons/git/git-original-wordmark.svg" title="Git" **alt="Git" width="40" height="40"/>
</div>

I am skilled in:
<div>
    <img src="https://github.com/devicons/devicon/blob/master/icons/c/c-original.svg"  title="C" alt="C" width="40" height="40"/>&nbsp;
    <img src="https://github.com/devicons/devicon/blob/master/icons/rust/rust-original.svg"  title="rust" alt="rust" width="40" height="40"/>&nbsp;
    <img src="https://github.com/devicons/devicon/blob/master/icons/linux/linux-original.svg" title="Linux" **alt="Linux" width="40" height="40"/>
</div>

I am proficient in:
<div>
    <img src="https://github.com/devicons/devicon/blob/master/icons/cplusplus/cplusplus-original.svg"  title="C++" alt="C++" width="40" height="40"/>&nbsp;
    <img src="https://github.com/devicons/devicon/blob/master/icons/python/python-original.svg"  title="python" alt="python" width="40" height="40"/>&nbsp;
    <img src="https://github.com/devicons/devicon/blob/master/icons/java/java-original-wordmark.svg" title="Java" alt="Java" width="40" height="40"/>&nbsp;
    <img src="https://github.com/devicons/devicon/blob/master/icons/latex/latex-original.svg" title="LaTeX" **alt="LaTeX" width="40" height="40"/>
</div>

I am interested in:
<div>
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/3a/Neovim-mark.svg/492px-Neovim-mark.svg.png"  title="Neovim" alt="Neovim" width="40" height="40"/>&nbsp;
    <img src="https://github.com/devicons/devicon/blob/master/icons/haskell/haskell-original.svg" title="haskell" **alt="haskell" width="40" height="40"/>
    <img src="https://github.com/devicons/devicon/blob/master/icons/julia/julia-original.svg" title="julia" **alt="julia" width="40" height="40"/>
    <img src="https://github.com/devicons/devicon/blob/master/icons/scala/scala-original.svg" title="scala" **alt="scala" width="40" height="40"/>
    <img src="https://github.com/devicons/devicon/blob/master/icons/llvm/llvm-original.svg" title="llvm" **alt="llvm" width="40" height="40"/>
<div/>


[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=LordGoatius&layout=compact&theme=vision-friendly-dark&hide=javascript,html,lua,makefile&langs_count=6)](https://github.com/anuraghazra/github-readme-stats)
