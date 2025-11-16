# service-Figma-create
Figmaでデザインカンプ作成

graph TD
    root[project/]
    
    root --> src[src/]
    root --> public[public/]
    root --> config[設定ファイル]
    
    src --> components[components/]
    src --> pages[pages/]
    src --> utils[utils/]
    src --> styles[styles/]
    
    components --> Header[Header.tsx]
    components --> Footer[Footer.tsx]
    components --> Button[Button.tsx]
    
    pages --> index[index.tsx]
    pages --> about[about.tsx]
    
    utils --> api[api.ts]
    utils --> helpers[helpers.ts]
    
    public --> images[images/]
    public --> favicon[favicon.ico]
    
    config --> package[package.json]
    config --> tsconfig[tsconfig.json]
    config --> gitignore[.gitignore]
