# Planners-disasters

# first disaster: PANDA

[error] (compile:compileIncremental) java.lang.NullPointerException
Project loading failed: (r)etry, (q)uit, (l)ast, or (i)gnore? i
[warn] Ignoring load failure: no project loaded.
[error] Expected ID character
[error] Not a valid command: main (similar: alias)
[error] main/assembly
[error] 

# second disaster: DiNo

Compilation error:

make[1]: *** [Makefile:27: pddl+.o] Error 1
make[1]: Leaving directory '/home/chuismi/Desktop/robotica/tercero/segundocuat/planificacion/DiNo/src/DiNo_parser'
make: *** [Makefile:7: pddl2upm] Error 2

# third disaster: UPMurphi:

Same error as dino


# fourth disaster: jshop:

massive java error

# FIFTH disaster: SMT:

more than an hour compiling z3 and then piranha is not working. Too much dependencies.

# sixth disaster: SMT:

c error: ...
__gnu_cxx::_normal_iterator<TIM::Property*, std::vector<TIM::Property, std::allocator<TIM::Property*> > >)':
TimSupport.cpp:(.text.ZN10CascadeMapIPN3TIM8PropertyENS0_13PropertyStateEE8forceGetIN9gnu_cxx17normal_iteratorIPS2_St6vectorIS2_SaIS2_EEEEEERPS3_T_SF[ZN10CascadeMapIPN3TIM8PropertyENS0_13PropertyStateEE8forceGetIN9gnu_cxx17normal_iteratorIPS2_St6vectorIS2_SaIS2_EEEEEERPS3_T_SF]+0x80): referencia a `operator new(unsigned int)' sin definir
/usr/bin/ld: lib/libInst.a(TimSupport.o):TimSupport.cpp:(.text.ZSt8for_eachISt23_Rb_tree_const_iteratorIPN3TIM14TransitionRuleEENS1_19extendWithStateRuleEET0_T_S7_S6[ZSt8for_eachISt23_Rb_tree_const_iteratorIPN3TIM14TransitionRuleEENS1_19extendWithStateRuleEET0_T_S7_S6]+0x311): más referencias a `operator new(unsigned int)' sin definir a continuación

optic: make error


No more planners unused with homepage.
