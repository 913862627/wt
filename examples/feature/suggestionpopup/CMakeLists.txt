IF(NOT WT_NO_STD_WSTRING)

WT_ADD_EXAMPLE(suggestionpopup.wt SuggestionPopup.C)

#
# If you have Wt installed somehwere, you should use the
# installed Wt header files for your own Wt projects.
# e.g. INCLUDE_DIRECTORIES(/usr/local/include)
# instead of the following:
#
INCLUDE_DIRECTORIES(${WT_SOURCE_DIR}/src)

ENDIF(NOT WT_NO_STD_WSTRING)
