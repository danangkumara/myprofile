graph TD
    A[Fase 1: Persiapan<br/>2024-2025] --> B[Fase 2: Pengembangan<br/>2025-2027]
    B --> C[Fase 3: Implementasi<br/>2027-2029]
    C --> D[Fase 4: Optimalisasi<br/>2029-2032]
    D --> E[Fase 5: Skalabilitas<br/>2032+]

    %% Fase 1 Details
    A --> A1[📊 Data Collection<br/>- Soil sensors<br/>- Weather stations<br/>- Drone imagery]
    A --> A2[🔧 Infrastruktur IoT<br/>- LoRaWAN network<br/>- Edge computing<br/>- 5G connectivity]
    A --> A3[🧠 Baseline AI Models<br/>- Soil moisture prediction<br/>- Crop health detection<br/>- Yield estimation]

    %% Fase 2 Details
    B --> B1[🤖 Advanced AI<br/>- CNN untuk deteksi penyakit<br/>- LSTM untuk prediksi cuaca<br/>- Reinforcement Learning]
    B --> B2[🌱 Digital Twin<br/>- 3D farm modeling<br/>- Real-time simulation<br/>- Scenario testing]
    B --> B3[💧 Smart Irrigation<br/>- Variable Rate Irrigation<br/>- Drip optimization<br/>- Water usage AI]

    %% Fase 3 Details
    C --> C1[🚜 Autonomous Farming<br/>- AI-guided robots<br/>- Precision planting<br/>- Selective harvesting]
    C --> C2[📈 Predictive Analytics<br/>- Market price prediction<br/>- Supply chain optimization<br/>- Risk assessment]
    C --> C3[🔒 Security Framework<br/>- Blockchain data integrity<br/>- Cybersecurity IoT<br/>- Data privacy]

    %% Fase 4 Details
    D --> D1[⚡ Energy Optimization<br/>- Solar-powered IoT<br/>- Energy harvesting<br/>- AI power management]
    D --> D2[🌍 Sustainability Metrics<br/>- Carbon footprint tracking<br/>- Biodiversity impact<br/>- Resource efficiency]
    D --> D3[🎯 Multi-crop Adaptation<br/>- Crop rotation AI<br/>- Intercropping models<br/>- Soil health recovery]

    %% Fase 5 Details
    E --> E1[☁️ Cloud Federation<br/>- Multi-farm data sharing<br/>- Federated learning<br/>- Regional insights]
    E --> E2[🤝 Policy Integration<br/>- Government subsidies<br/>- Carbon credit system<br/>- Farmer cooperatives]
    E --> E3[🚀 Commercialization<br/>- SaaS platform<br/>- API marketplace<br/>- Global expansion]

    %% Styling
    classDef phase1 fill:#e1f5fe
    classDef phase2 fill:#f3e5f5
    classDef phase3 fill:#e8f5e8
    classDef phase4 fill:#fff3e0
    classDef phase5 fill:#fce4ec

    class A,A1,A2,A3 phase1
    class B,B1,B2,B3 phase2
    class C,C1,C2,C3 phase3
    class D,D1,D2,D3 phase4
    class E,E1,E2,E3 phase5
