# $FreeBSD$

.include <bsd.own.mk>

LIB=	llvmsparccodegen

SRCDIR=	lib/Target/Sparc
SRCS=	DelaySlotFiller.cpp \
	SparcAsmPrinter.cpp \
	SparcCodeEmitter.cpp \
	SparcFrameLowering.cpp \
	SparcISelDAGToDAG.cpp \
	SparcISelLowering.cpp \
	SparcInstrInfo.cpp \
	SparcJITInfo.cpp \
	SparcMCInstLower.cpp \
	SparcMachineFunctionInfo.cpp \
	SparcRegisterInfo.cpp \
	SparcSelectionDAGInfo.cpp \
	SparcSubtarget.cpp \
	SparcTargetMachine.cpp \
	SparcTargetObjectFile.cpp

TGHDRS=	Intrinsics \
	SparcGenAsmWriter \
	SparcGenCallingConv \
	SparcGenCodeEmitter \
	SparcGenDAGISel \
	SparcGenInstrInfo \
	SparcGenMCCodeEmitter \
	SparcGenRegisterInfo \
	SparcGenSubtargetInfo

.include "../clang.lib.mk"
