/* eslint-disable react/prop-types */
/* eslint-disable react/function-component-definition */
/**
=========================================================
* Material Dashboard 2 React - v2.1.0
=========================================================

* Product Page: https://www.creative-tim.com/product/material-dashboard-react
* Copyright 2022 Creative Tim (https://www.creative-tim.com)

Coded by www.creative-tim.com

 =========================================================

* The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
*/

// Material Dashboard 2 React components
import MDBox from "components/MDBox";
import MDTypography from "components/MDTypography";
import MDAvatar from "components/MDAvatar";
import MDBadge from "components/MDBadge";

// Images
import Sampling from "assets/images/sampling.png";
import Buyer from "assets/images/buyer.png";
import Testing from "assets/images/testing.png";
import Work from "assets/images/work.png";
import Pipeline from "assets/images/pipeline.png";
import Warehouse from "assets/images/warehouse.png";

export default function data() {
  const Author = ({ image, name, email }) => (
    <MDBox display="flex" alignItems="center" lineHeight={1}>
      <MDAvatar src={image} name={name} size="sm" variant="rounded" />
      <MDBox ml={2} lineHeight={1}>
        <MDTypography display="block" variant="button" fontWeight="medium">
          {name}
        </MDTypography>
        <MDTypography variant="caption">{email}</MDTypography>
      </MDBox>
    </MDBox>
  );

  // const Job = ({ title, description }) => (
  //   <MDBox lineHeight={1} textAlign="left">
  //     <MDTypography display="block" variant="caption" color="text" fontWeight="medium">
  //       {title}
  //     </MDTypography>
  //     <MDTypography variant="caption">{description}</MDTypography>
  //   </MDBox>
  // );

  return {
    columns: [
      { Header: "modules", accessor: "author", width: "45%", align: "left" },
      { Header: "costing", accessor: "function", align: "left" },
      { Header: "status", accessor: "status", align: "center" },
      { Header: "update date", accessor: "employed", align: "center" },
      { Header: "action", accessor: "action", align: "center" },
    ],

    rows: [
      {
        author: <Author image={Sampling} name="Sampling" email="sample approved" />,
        // function: <Job title="₹10,000" description="Organization" />,
        function: (
          <MDTypography component="a" href="#" variant="button" color="text" fontWeight="medium">
            ₹20,500
          </MDTypography>
        ),
        status: (
          <MDBox ml={-1}>
            <MDBadge badgeContent="approved" color="success" variant="gradient" size="sm" />
          </MDBox>
        ),
        employed: (
          <MDTypography component="a" href="#" variant="caption" color="text" fontWeight="medium">
            23/04/18
          </MDTypography>
        ),
        action: (
          <MDTypography component="a" href="#" variant="caption" color="text" fontWeight="medium">
            Edit
          </MDTypography>
        ),
      },
      {
        author: <Author image={Buyer} name="Buyer Order" email="50,000 units" />,
        // function: <Job title="Programator" description="Developer" />,
        function: (
          <MDTypography component="a" href="#" variant="button" color="text" fontWeight="medium">
            ₹50,000
          </MDTypography>
        ),
        status: (
          <MDBox ml={-1}>
            <MDBadge badgeContent="approved" color="success" variant="gradient" size="sm" />
          </MDBox>
        ),
        employed: (
          <MDTypography component="a" href="#" variant="caption" color="text" fontWeight="medium">
            11/01/19
          </MDTypography>
        ),
        action: (
          <MDTypography component="a" href="#" variant="caption" color="text" fontWeight="medium">
            Edit
          </MDTypography>
        ),
      },
      {
        author: <Author image={Testing} name="Testing Tooling" email="approved by X Labs" />,
        // function: <Job title="Executive" description="Projects" />,
        function: (
          <MDTypography component="a" href="#" variant="button" color="text" fontWeight="medium">
            ₹10,500
          </MDTypography>
        ),
        status: (
          <MDBox ml={-1}>
            <MDBadge badgeContent="approved" color="success" variant="gradient" size="sm" />
          </MDBox>
        ),
        employed: (
          <MDTypography component="a" href="#" variant="caption" color="text" fontWeight="medium">
            19/09/17
          </MDTypography>
        ),
        action: (
          <MDTypography component="a" href="#" variant="caption" color="text" fontWeight="medium">
            Edit
          </MDTypography>
        ),
      },
      {
        author: <Author image={Work} name="Work Order" email="Pending" />,
        // function: <Job title="Programator" description="Developer" />,
        function: (
          <MDTypography component="a" href="#" variant="button" color="text" fontWeight="medium">
            ₹20,500
          </MDTypography>
        ),
        status: (
          <MDBox ml={-1}>
            <MDBadge badgeContent="approved" color="success" variant="gradient" size="sm" />
          </MDBox>
        ),
        employed: (
          <MDTypography component="a" href="#" variant="caption" color="text" fontWeight="medium">
            24/12/08
          </MDTypography>
        ),
        action: (
          <MDTypography component="a" href="#" variant="caption" color="text" fontWeight="medium">
            Edit
          </MDTypography>
        ),
      },
      {
        author: <Author image={Pipeline} name="Pipeline" email="Started" />,
        // function: <Job title="Manager" description="Executive" />,
        function: (
          <MDTypography component="a" href="#" variant="button" color="text" fontWeight="medium">
            ₹0
          </MDTypography>
        ),
        status: (
          <MDBox ml={-1}>
            <MDBadge badgeContent="pending" color="dark" variant="gradient" size="sm" />
          </MDBox>
        ),
        employed: (
          <MDTypography component="a" href="#" variant="caption" color="text" fontWeight="medium">
            04/10/21
          </MDTypography>
        ),
        action: (
          <MDTypography component="a" href="#" variant="caption" color="text" fontWeight="medium">
            Edit
          </MDTypography>
        ),
      },
      {
        author: <Author image={Warehouse} name="Warehouse" email="DMTR" />,
        // function: <Job title="Programator" description="Developer" />,
        function: (
          <MDTypography component="a" href="#" variant="button" color="text" fontWeight="medium">
            ₹2,00,500
          </MDTypography>
        ),
        status: (
          <MDBox ml={-1}>
            <MDBadge badgeContent="pending" color="dark" variant="gradient" size="sm" />
          </MDBox>
        ),
        employed: (
          <MDTypography component="a" href="#" variant="caption" color="text" fontWeight="medium">
            14/09/20
          </MDTypography>
        ),
        action: (
          <MDTypography component="a" href="#" variant="caption" color="text" fontWeight="medium">
            Edit
          </MDTypography>
        ),
      },
    ],
  };
}
