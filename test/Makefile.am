noinst_PROGRAMS = unittest vm_unittest

TESTS = unittest vm_unittest

unittest_SOURCES = \
	unittest.cpp \
	test_Address_Registration_Guard.cpp \
	test_Allocation_Strategies.cpp \
	test_Array.cpp \
	test_Builtin_Object.cpp \
	test_Class.cpp \
	test_Constructor.cpp \
	test_Critical_Guard.cpp \
	test_Data_Object.cpp \
	test_Enum.cpp \
	test_Exception.cpp \
	test_Hash.cpp \
	test_Identifier.cpp \
	test_Jump_Tag.cpp \
	test_Module.cpp \
	test_Object.cpp \
	test_String.cpp \
	test_Struct.cpp \
	test_Symbol.cpp \
	test_To_From_Ruby.cpp

vm_unittest_SOURCES = \
	unittest.cpp \
	test_VM.cpp

AM_CPPFLAGS = \
	-I.. \
	$(RUBY_CPPFLAGS)

AM_LDFLAGS = \
	$(RUBY_LDFLAGS) \
	-L../rice

LIBS = \
	-lrice \
	$(RUBY_LIBS) \
	$(RUBY_LIBRUBYARG)

