gantt
    title Harmony Wall Project
    dateFormat  YYYY-MM-DD
    axisFormat  %b %Y
    todayMarker off

    section Milestones
    Start                        :milestone, 2025-01-01,
    Planning/Req Complete        :milestone, 2025-04-01,
    UI/UX Mocks Complete         :milestone, 2025-04-01,
    Hardware Dev Complete        :milestone, 2025-06-01,
    Wall Backend Complete        :milestone, 2025-06-01,
    Wall Integrations Complete   :milestone, 2025-08-01,
    Hub Backend Complete         :milestone, 2025-08-01,
    Frontends Complete           :milestone, 2025-08-31,
    UATs Complete                :milestone, 2025-10-01,
    E2E Complete                 :milestone, 2025-12-01,
    Rollout Complete             :milestone, 2025-12-31,

    section Requirements & Planning
    Wall Software      :a1, 2025-01-01, 2025-02-01
    Wall Hardware      :a1, 2025-01-01, 2025-03-01
    Hub Software       :a9, 2025-02-01, 2025-03-31
    
    section Design & Prototyping
    UI/UX Mocks                  :a5, 2025-02-01, 2025-03-31
    Prototyping                  :a6, 2025-03-01, 2025-03-31

    section Hardware Dev
    Identify Specs & Suppliers   :a2, 2025-01-15, 2025-03-15
    Hardware Prototyping         :a3, 2025-02-01, 2025-03-31
    Testing & Iteration          :a4, 2025-04-01, 2025-05-31
    
    section Wall Software Dev
    Wall Backend Dev          :a7, 2025-02-01, 2025-05-31
    Wall Frontend Dev         :a8, 2025-05-01, 2025-08-31
    Integrate                 :a9, 2025-04-01, 2025-07-31
    UAT                       :a10, 2025-08-01, 2025-09-30
    
    section Hub Software Dev
    Hub Backend Dev           :a11, 2025-04-01, 2025-07-31
    Hub Frontend Dev          :a12, 2025-05-01, 2025-08-31
    UAT                       :a13, 2025-08-01, 2025-09-30
    
    section Testing & QA
    Component Testing            :a14, 2025-08-01, 2025-10-31
    End-to-End System Testing    :a15, 2025-10-01, 2025-11-30
    
    section Pilot Deployment
    Limited Deployment           :a16, 2025-11-01, 2025-11-30
    SW/HW Iteration              :a17, 2025-11-01, 2025-12-31
    
    section Rollout
    Full Rollout & Training      :a18, 2025-12-01, 2025-12-31

