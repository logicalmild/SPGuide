# SPGuide.js

### Data
// SPGuide.js for SharePoint 
// -------index------
// Section1: Query Data
            //GetCurrentPageName()[return string];
            //GetParameterByName(name)[return string];
            //Include(ElementID,Url);
            //IncludeComponent(ElementID,Component);
            //GetItemFromOtherSite(Site,Listname,Query)[data]
            //GetItemByRestAPI(Listname,Query)[data]
// Section2: Date Time
            //GetCurrentTime()[return time]
            //ConvertDateTime(DateTime)[return date]
            //ConvertDateOnly[return date]
            //ConvertDate(DateTime)[return date]
            //GetCurrentYear()[string]
            //GetCurrentDate()[date]
            //GetCurrentTime()[date]
            //SetTime(time)[date]
            //SetDateTime()[date]
// Section3: Operation String
// Section4: Generate
            //GenGUID()[return string];
            //generateUID()[return string]
// Section5: User and permission
            //AddCurrentUserToGroup(GroupID)[];
            //addUsersToGroup(usernames, GroupID)[];
            //CheckUserInGroupID(GroupID)[return bool];
            //GetAllUserFromGroupID(GroupID)[return object people];
            //removeUserFromGroup(userLoginName,GroupID,success,error)[];
// Section6: Validate data
            //SetRequireField(FieldID,TypeDom)[];