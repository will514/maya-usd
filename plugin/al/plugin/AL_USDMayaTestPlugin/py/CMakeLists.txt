mayaUsd_add_test(TestALUSDMayaPython_ProxyShape
    PYTHON_MODULE testProxyShape
    ENV
        "PXR_PLUGINPATH_NAME=${ADDITIONAL_PXR_PLUGINPATH_NAME}"
)

mayaUsd_add_test(TestALUSDMayaPython_Translators
    PYTHON_MODULE testTranslators
    ENV
        "PXR_PLUGINPATH_NAME=${ADDITIONAL_PXR_PLUGINPATH_NAME}"
)

mayaUsd_add_test(TestALUSDMayaPython_LayerManager
    PYTHON_MODULE testLayerManager
    ENV
        "PXR_PLUGINPATH_NAME=${ADDITIONAL_PXR_PLUGINPATH_NAME}"
)

mayaUsd_add_test(TestALUSDMayaPython_ImportModule
    PYTHON_MODULE testUSDMayaPythonModuleOnly
    ENV
        "PXR_PLUGINPATH_NAME=${ADDITIONAL_PXR_PLUGINPATH_NAME}"
    NO_STANDALONE_INIT
)