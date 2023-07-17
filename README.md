# SAP-ABAP-Program-for-PO-Status-Tracking
This is an SAP Advanced Business Application Programming (ABAP) project that aims to create a comprehensive report showing the open goods receipt and open invoice value for Purchase Orders (PO) based on a diverse set of selection criteria. This report assists in tracking and managing the purchasing process in an organization.
The report is divided into three major development stages: selection screen creation, data selection process, and ALV output display. These stages are reviewed and signed off at each completion.

# Selection Screen
The selection screen supports multi-value inputs for several parameters including Purchasing Org, Purchasing Group, Vendor, PO Document type, PO Document date, PO Number, Delivery complete status, and Final invoice status. It also allows a single value input for the layout, which can be saved and used for future report runs.

# Data Selection Process
The data selection process is based on the defined criteria from the selection screen. It pulls all the necessary details related to the POs that match the given criteria.

# ALV Output
The final output of the program is an ALV (ABAP List Viewer) based report which includes a comprehensive set of PO fields. The report utilises the cl_salv_table method for rendering the ALV output. Two of the report fields display icon indicators for the Delivery and Invoice status of the PO. There is also a color indicator feature for overdue deliveries with open quantity.

In addition, the PO number in the report acts as a hotspot, enabling navigation to ME23N transaction for that specific PO.
