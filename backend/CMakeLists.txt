set(
	KUN_UI_GRAPHICS_API
	"OPENGL"
	CACHE
		STRING
		"Graphics API backend: OPENGL, D3D11, VULKAN"
)
set_property(CACHE KUN_UI_GRAPHICS_API PROPERTY STRINGS OPENGL D3D11 VULKAN)

add_library(kun-ui src/kun-ui-frame.cpp)