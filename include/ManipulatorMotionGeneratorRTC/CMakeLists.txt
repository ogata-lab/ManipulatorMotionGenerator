set(hdrs ManipulatorMotionGeneratorRTC.h
    PARENT_SCOPE
    TrajectoryPlannerSVC_impl.h
    )

install(FILES ${hdrs} DESTINATION ${INC_INSTALL_DIR}/${PROJECT_NAME_LOWER}
    COMPONENT library)

