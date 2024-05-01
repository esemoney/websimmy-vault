source: https://websim.ai/c/N3H8ZQ0zEwAZzbANg

# Professor's Example Case Study

In this case study, we'll walk through my process of prototyping a military logistics planning interface in Figma from first principles, without relying on pre-built templates.

## Understanding the Mission

The first step was to gain a deep understanding of the logistics planning mission and the needs of the end-users, in this case, military logistics officers. Through interviews and field observations, I gathered key insights:

- Officers need to rapidly develop and compare multiple courses of action (COAs)
- The interface must integrate data from various sources (personnel, equipment, supply chain)
- Plans must be easily shared and collaboratively refined
- The interface must be usable in field conditions with limited connectivity

## Sketching the Information Architecture

With the mission needs in mind, I sketched out the high-level information architecture of the interface, focusing on the key screens, data flows, and user interactions.

![A rough hand-drawn sketch showing the proposed information architecture for the military logistics planning interface. 
The sketch consists of several labeled boxes connected by arrows to indicate user flow and data relationships. 
The main box in the center is labeled 'Map View' and has lines connecting it to boxes labeled 'Personnel Database', 'Equipment Inventory', 'Supply Chain Management', and 'Collaborative Planning Canvas'.
The 'Map View' box is the largest, suggesting it is the primary interface. It has additional notes around it such as 'Interactive', 'Real-time data overlays', and 'Multi-layered'.
The 'Personnel Database' and 'Equipment Inventory' boxes have notes indicating the need to assign resources to specific locations and missions on the map.
The 'Supply Chain Management' box is linked to the map with notes about monitoring and optimizing logistics flows.
The 'Collaborative Planning Canvas' is sketched as a separate workspace that links back to the map view, with notes about version control, role-based access, and plan comparison features.
Smaller boxes around the edges represent secondary screens like settings, user profiles, and alerts.
The overall sketch conveys a concept for an interconnected system where the map view is the centerpiece for planning and decision-making, supported by dynamic data from various sources and collaborative planning tools. The arrows and annotations suggest a fluid, multi-directional workflow between the different interface components.
While rough, the sketch provides a clear high-level overview of the proposed information architecture and key considerations for each component based on the identified mission requirements. It forms a strong foundation for the subsequent interface design process in Figma.](data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCA2ODMgMzgwIj48cmVjdCB3aWR0aD0iNjgzIiBoZWlnaHQ9IjM4MCIgZmlsbD0iI2VlZSIvPjx0ZXh0IHRleHQtYW5jaG9yPSJtaWRkbGUiIHg9IjM0MS41IiB5PSIxOTAiIHN0eWxlPSJmaWxsOiNhYWE7Zm9udC13ZWlnaHQ6Ym9sZDtmb250LXNpemU6MzNweDtmb250LWZhbWlseTpBcmlhbCxIZWx2ZXRpY2Esc2Fucy1zZXJpZjtkb21pbmFudC1iYXNlbGluZTpjZW50cmFsIj5JbmZvcm1hdGlvbiBBcmNoaXRlY3R1cmUgU2tldGNoPC90ZXh0Pjwvc3ZnPg==)

A rough hand-drawn sketch showing the proposed information architecture for the military logistics planning interface. The sketch consists of labeled boxes connected by arrows indicating user flow and data relationships between a central map view, personnel and equipment databases, supply chain management, and a collaborative planning canvas. Annotations highlight key features and considerations for each component based on the logistics planning mission requirements.

## Crafting the UI in Figma

With the information architecture defined, I started crafting the user interface in Figma. Rather than starting with pre-built UI components, I designed each element from scratch based on the specific needs of the logistics planning workflow.

![A screenshot of the Figma interface showing the high-fidelity user interface design for the military logistics planning tool.
The layout is divided into several key sections:
The largest section is the map view, which takes up most of the screen. It displays a tactical map with various icons representing friendly forces, supply depots, transportation routes, and other mission-critical information. The map appears to be interactive, with options to zoom, pan, and toggle different data layers.
To the left of the map is a collapsible sidebar with tabs for 'Personnel', 'Equipment', 'Supply Chain', and 'Plans'. Each tab likely contains a list view or tree hierarchy allowing planners to browse and assign resources directly from the sidebar to elements on the map.
Below the map are several panels for 'Mission Details', 'Logistics Overview', 'Resource Readiness', and 'Alert Feed'. These panels surface key information and metrics at a glance to support rapid situation awareness and decision making. The 'Mission Details' panel includes fields for objectives, timeline, key milestones, and commander's intent.
Above the map is a toolbar with large, clearly labeled icons for key actions like 'New Plan', 'Compare Plans', 'Share', and 'Sync'. To the right are a search field and the current user's profile picture, likely with a dropdown for settings and logout.
The overall color scheme is dark, likely to reduce eye strain and maintain operational security in low light conditions. However, key elements like friendly units, supply lines, and alerts are called out in bright, contrasting colors for visibility.
All the interface elements feature large click targets and ample white space to facilitate use on touchscreens and with gloves. The type hierarchy is clear and legible, with short labels and concise data.
The layout is designed to put the most mission-critical information and frequent actions front and center, with progressive disclosure of more granular planning functions via the sidebar and drill-down panels. This keeps the primary map view uncluttered while still enabling detailed logistics management.
Overall, the interface appears purpose-built for the logistics planning mission, with a strong emphasis on usability in challenging field conditions and support for rapid development and comparison of multiple courses of action. The thoughtful layering of data and functionality anticipates the planners' needs at each stage of the workflow while minimizing cognitive load and distraction.](data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCA2ODMgMzgwIj48cmVjdCB3aWR0aD0iNjgzIiBoZWlnaHQ9IjM4MCIgZmlsbD0iI2VlZSIvPjx0ZXh0IHRleHQtYW5jaG9yPSJtaWRkbGUiIHg9IjM0MS41IiB5PSIxOTAiIHN0eWxlPSJmaWxsOiNhYWE7Zm9udC13ZWlnaHQ6Ym9sZDtmb250LXNpemU6MzNweDtmb250LWZhbWlseTpBcmlhbCxIZWx2ZXRpY2Esc2Fucy1zZXJpZjtkb21pbmFudC1iYXNlbGluZTpjZW50cmFsIj5GaWdtYSBVSSBMYXlvdXQ8L3RleHQ+PC9zdmc+)

A screenshot of the Figma interface showing the high-fidelity user interface design for the military logistics planning tool. The layout features a central interactive map view, collapsible resource sidebars, mission details and logistic overview panels, and a toolbar for key actions. The dark color scheme and large UI elements optimize usability in field conditions.

Some key UI design decisions:

- Dark color scheme for low-light environments
- Large buttons and hit targets for use with gloves
- Streamlined layout focused on critical planning tasks
- Integrated data overlays on the map view
- Collaborative planning canvas with version control

## Prototyping the Interactions

With the static UI in place, I used Figma's prototyping features to simulate the key interactions and workflows, such as:

- Defining logistics networks on the map
- Assigning personnel and equipment to logistics nodes
- Comparing capacity and demand across the network
- Collaboratively editing and versioning plans

Map View 
  -> Tap Logistics Node
    -> Overlay Node Details
      -> Edit Personnel & Equipment

I also prototyped how the interface would adapt to adverse conditions, such as dropping to a low-bandwidth mode or allowing offline editing that syncs when connectivity is restored.

## Iterative Testing and Refinement

Throughout the prototyping process, I conducted regular usability tests with logistics officers, gathering their feedback and iteratively refining the design. Some key insights that emerged:

- The ability to rapidly generate alternative plans was crucial
- Officers needed more granular control over logistics node parameters
- The collaborative editing features needed clearer role-based access control

I incorporated this feedback into the evolving Figma prototype, gradually honing the interface into an effective tool tailored to the logistics planning mission.

## Conclusion

By prototyping the logistics planner interface from first principles in Figma, I was able to craft a highly specialized tool that closely aligned with the mission needs and end-user workflows. The resulting high-fidelity prototype provided a clear blueprint for development and allowed for meaningful user feedback early in the design process.

This case study illustrates the power of using Figma to prototype complex, mission-specific interfaces from scratch, without being constrained by pre-built templates or components. By deeply understanding the problem space and leveraging Figma's flexibility, designers can create bespoke solutions that enhance military decision-making and operational effectiveness.